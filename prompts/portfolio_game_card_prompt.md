# Portfolio Game Card Generator — Prompt chuẩn hóa

## Mục đích

Skill này tạo thẻ bài game dạng concept cho portfolio cá nhân. Ưu tiên:

- thiết kế đồng bộ theo từng archive
- dễ cắt ghép và remove background
- không có chi tiết vượt khỏi card area
- không gộp front và back trong cùng một asset
- không tự dùng ảnh cũ hoặc master chưa được cung cấp

---

# 1. Quy trình bắt buộc

Không generate front, back và mockup trong cùng một lượt.

Mỗi lượt chỉ chạy đúng một mode:

1. **FRONT ASSET MODE** — tạo đúng một mặt trước.
2. **BACK ASSET MODE** — tạo đúng một mặt sau.
3. **MOCKUP MODE** — dùng front và back đã duyệt để dựng presentation.

Không tạo split layout, comparison sheet, front-and-back pair hoặc hai card trong cùng một ảnh asset.

---

# 2. Quy ước archive và master

Dùng quy ước tên file:

```text
<archive_name>_master_front.png
<archive_name>_master_back.png
```

Ví dụ:

```text
ember_master_front.png
ember_master_back.png

frost_master_front.png
frost_master_back.png
```

Không dùng dấu `/` trong tên file.

## Master availability check

Chỉ được dùng master khi file tương ứng thực sự được cung cấp hoặc có sẵn trong Project Sources.

Không được tự suy luận hoặc lấy master từ:

- ảnh đã generate trước đó
- ảnh trong lượt chat cũ
- ví dụ trong prompt
- visual memory
- archive khác

Nếu `Reference Mode: Master` nhưng thiếu file bắt buộc, phải dừng và yêu cầu upload file.

Nếu `Reference Mode: None`, không được dùng bất kỳ ảnh card cũ nào làm reference.

---

# 3. Thứ tự ưu tiên bắt buộc

Khi có xung đột, luôn ưu tiên theo thứ tự sau:

1. **Card Area Lock**
2. **Layout Containment**
3. **Archive Master Consistency**
4. **Visual polish and creativity**

Nếu master có chi tiết nhô ra khỏi card, không được sao chép lỗi đó. Giữ style của master nhưng phải đưa chi tiết vào trong card area.

---

# 4. Non-negotiable Card Area Lock

Quy tắc này luôn bật trong mọi mode và không được bỏ qua.

```text
NON-NEGOTIABLE CARD AREA LOCK

Every generated card must fit entirely inside one fixed, simple, closed rounded-rectangle card area.

This rule always applies and cannot be disabled.

No visual element may extend beyond the physical card boundary, including:
- character artwork
- items and weapons
- flames, particles, glow, smoke, and shadows
- title decorations
- gems, crests, badges, tabs, and icons
- frame ornaments
- corner decorations
- logos
- background shapes

The outer card silhouette must remain one uninterrupted rounded rectangle with no protrusions, extensions, raised ornaments, die-cut shapes, or border-breaking artwork of any kind.

All design layers must be clipped to the card area.

Keep a minimum internal safety margin of 3–5% inside every outer card edge.

If an element does not fit, scale it down, move it inward, flatten it, or simplify it.
Never expand it outside the card area.

Containment is more important than drama, scale, decoration, or fidelity to a protruding reference detail.

If the master reference contains any protruding or border-breaking element, do not reproduce that defect. Preserve the master’s visual style, but move, scale, flatten, or simplify the element so it remains fully inside the locked card area.
```

---

# 5. Prompt — Front Asset Mode

```text
TASK MODE: FRONT ASSET ONLY

Generate exactly one image containing exactly one front card.
Do not generate a back card.
Do not generate a mockup.
Do not place a second card anywhere in the image.
Do not create a split composition, comparison sheet, presentation board, or front-and-back pair.

INPUT
- Card Name: "{CARD_NAME}"
- Element: "{ELEMENT}"
- Rarity: "{RARITY}"
- Archive Name: "{ARCHIVE_NAME}"
- Reference Mode: "{REFERENCE_MODE}"

SUBJECT IMAGE
Use only the newly provided monster, item, resource, or logo image as the subject.
Preserve its recognizable identity and overall silhouette.

REFERENCE CHECK
If Reference Mode is Master:
- use only "{ARCHIVE_NAME}_master_front.png"
- the file must be explicitly available in the current request or Project Sources
- do not use the back master
- do not use previous generated cards or earlier conversation images
- if the file is missing, stop and ask the user to provide it

If Reference Mode is None:
- do not use any previous generated card as reference
- do not infer a missing master
- follow only the current subject image and this prompt

LOCKED FRONT TEMPLATE
When the front master is available, preserve:
- card aspect ratio
- rounded-rectangle silhouette
- frame style and border thickness
- corner radius
- title panel position
- illustration window position
- rarity position
- element position
- HP / ATK / DEF positions
- spacing and visual hierarchy
- archive-specific visual language

Replace only:
- subject illustration
- card name
- element
- rarity
- HP / ATK / DEF values
- permitted accent colours

NON-NEGOTIABLE CARD AREA LOCK
Every visual layer must remain fully inside one simple closed rounded-rectangle card area.
No protrusions of any kind.
No raised crest, gem, tab, badge, icon, flame, ornament, weapon, particle, glow, or decorative layer may cross the physical card edge.
All layers must be clipped to the card area.
Keep 3–5% internal padding from the outer card boundary.

FRONT LAYOUT CONTAINMENT
Use three protected zones:
1. title and rarity zone
2. central illustration zone
3. element and stats zone

The subject and all attached objects must remain fully inside the central illustration window.
The illustration window acts as a hard clipping mask.

No part of the subject may overlap or touch:
- title panel
- rarity badge
- element bar
- HP / ATK / DEF row
- outer frame
- corner decoration

This includes:
- head and hat
- hands and feet
- weapons and staffs
- wings and tails
- flames and smoke
- particles and glow
- spell effects and shadows

Keep 5–8% internal safety margin inside the illustration window.
Scale the subject down when necessary.
Remove or simplify visual effects that cannot fit.
No pop-out art, no border break, and no cross-zone overlap.

CARD CONTENT
- top: card name
- centre: main illustration
- bottom: element and HP / ATK / DEF
- all visible text in English
- no skill description or effect text

STAT GENERATION
Use a 1–20 scale:
- Common: 4–9
- Rare: 8–14
- Epic: 13–20

Adjust distribution based on visual impression:
- agile or offensive: slightly higher ATK
- heavy or defensive: slightly higher HP or DEF
- balanced: more even values

OUTPUT RULES
- exactly one front card
- straight-on orthographic view
- centred and fully visible
- flat production asset
- plain solid background with strong edge contrast
- no drop shadow
- no cast shadow
- no glow outside the card
- no perspective
- no tabletop, hand, stand, or environment
- no object or decoration outside the card silhouette
```

---

# 6. Prompt — Back Asset Mode

```text
TASK MODE: BACK ASSET ONLY

Generate exactly one image containing exactly one back card.
Do not generate a front card.
Do not generate a character or subject illustration.
Do not generate a mockup.
Do not place a second card anywhere in the image.
Do not create a split composition, comparison sheet, presentation board, or front-and-back pair.

INPUT
- Project Name: "{PROJECT_NAME}"
- Archive Name: "{ARCHIVE_NAME}"
- Reference Mode: "{REFERENCE_MODE}"

REFERENCE CHECK
If Reference Mode is Master:
- use only "{ARCHIVE_NAME}_master_back.png"
- the file must be explicitly available in the current request or Project Sources
- do not use the front master or subject image
- do not use previous generated cards or earlier conversation images
- if the file is missing, stop and ask the user to provide it

If Reference Mode is None:
- do not use any previous generated card as reference
- do not infer a missing master
- follow only this prompt

LOCKED BACK TEMPLATE
When the back master is available, preserve:
- card aspect ratio
- rounded-rectangle silhouette
- frame style and border thickness
- corner radius
- logo area
- pattern layout
- spacing
- archive-specific visual language

Only replace the project text/logo when necessary.

NON-NEGOTIABLE CARD AREA LOCK
Every visual layer must remain fully inside one simple closed rounded-rectangle card area.
No protrusions of any kind.
No crest, gem, tab, logo, icon, glow, ornament, line, pattern, or decorative layer may cross the physical card edge.
All layers must be clipped to the card area.
Keep 3–5% internal padding from every outer edge.

BACK CONTENT
- project name as a clean text logo
- minimal decorative composition
- thin frame consistent with the archive master
- all visible text in English

OUTPUT RULES
- exactly one back card
- straight-on orthographic view
- centred and fully visible
- flat production asset
- plain solid background with strong edge contrast
- no drop shadow
- no cast shadow
- no glow outside the card
- no perspective
- no tabletop, hand, stand, or environment
- no object or decoration outside the card silhouette
```

---

## 6B. Back Archive Variant

```text
TASK MODE: BACK ARCHIVE VARIANT

Use the provided existing back card as the single structural reference.

Generate exactly one new back card for the target archive.

Preserve:
- card aspect ratio
- rounded-rectangle silhouette
- corner radius
- frame thickness
- logo position
- logo scale
- spacing
- pattern hierarchy
- overall back-card layout

Adapt only:
- archive colour palette
- archive emblem or motif
- internal pattern details
- permitted decorative accents
- archive name or project text when requested

The new back must look like a coordinated archive variation of the source back, not a completely redesigned card.

NON-NEGOTIABLE CARD AREA LOCK:
- every layer must remain inside one simple closed rounded rectangle
- no crest, gem, icon, ornament, glow, pattern, or frame detail may protrude beyond the card boundary
- keep 3–5% internal safety padding
- no drop shadow
- no perspective
- no environment
- generate exactly one flat back card asset
```

---

# 7. Prompt — Portfolio Mockup Mode

```text
TASK MODE: PORTFOLIO MOCKUP

Use only the provided, already-approved front asset and back asset.

Do not redraw, regenerate, reinterpret, restyle, or alter either card face.
Do not change:
- text
- numbers
- illustration
- frame
- colours
- proportions
- layout

Creative presentation is allowed around the cards.

You may use:
- perspective
- card rotation
- overlapping placement
- soft cast shadows
- realistic contact shadows
- depth
- studio lighting
- gradients
- textured or decorative backgrounds
- podiums or display surfaces
- tasteful particles or environmental effects
- archive-themed props and scenery

All presentation effects must remain outside the printed card artwork and must not modify the card faces.

Show exactly:
- one front card
- one back card

The cards must remain separate physical objects.
Do not merge the front and back into one card design.
Do not generate replacement production assets.
```

---

# 8. Input ngắn dùng hằng ngày

## Tạo front có master

```text
Task Mode: Front Asset
Reference Mode: Master
Archive Name: ember
Card Name: Ignimor
Element: Fire
Rarity: Common
```

Đính kèm:

- ảnh subject mới
- `ember_master_front.png`

## Tạo front chưa có master

```text
Task Mode: Front Asset
Reference Mode: None
Archive Name: ember
Card Name: Ignimor
Element: Fire
Rarity: Common
```

Đính kèm ảnh subject mới. Không dùng ảnh card cũ làm reference.

## Tạo back variant

```text
Mode: Back Archive Variant
Source Back: global_master_back.png
Target Archive: frost
Project Name: Ember Archive
Element Theme: Ice
```

Đính kèm `global_master_back.png`.

## Tạo mockup

```text
Task Mode: Portfolio Mockup
```

Đính kèm front asset và back asset đã duyệt.

---

# 9. Phản hồi khi thiếu master

```text
I cannot start Master Reference Mode because the required master file is missing:
- {ARCHIVE_NAME}_master_front.png
```

hoặc:

```text
I cannot start Master Reference Mode because the required master file is missing:
- {ARCHIVE_NAME}_master_back.png
```

Yêu cầu người dùng upload file hoặc đổi sang `Reference Mode: None`.
