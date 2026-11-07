# Prompt tối ưu cho AI tạo ảnh – Portfolio Game Card

## Mục đích
Prompt này dùng để tạo **thẻ bài game dạng concept** cho **portfolio cá nhân**. Kết quả ưu tiên **đẹp, gọn, đồng bộ, có cảm giác như một dự án card game**, không cần phức tạp như game thật.

---

## Cách dùng
Thay các phần trong ngoặc nhọn bằng thông tin của bạn:

- `{CARD_NAME}`: tên thẻ
- `{ELEMENT}`: hệ/nguyên tố
- `{RARITY}`: Common / Rare / Epic
- `{PROJECT_NAME}`: tên dự án để hiện ở mặt sau
- `{INPUT_SUBJECT}`: mô tả ngắn ảnh đầu vào nếu cần

Nếu công cụ hỗ trợ ảnh tham chiếu, hãy **đính kèm ảnh đầu vào** và dùng prompt dưới đây.

---

## Prompt hoàn chỉnh (bản tối ưu cho AI tạo ảnh)

```text
Create a polished portfolio-quality game card concept based on the provided input image.

The card style should be cute, minimal, clean, modern, and more refined than a simple casual card game. The design should feel professional and visually cohesive, suitable for a designer portfolio. Use a single unified card format.

Generate a complete card presentation that includes:
1. a clear front view of the card,
2. a clear back view of the card,
3. a polished portfolio mockup presentation showing both front and back.

Main subject:
- Use the provided input image as the main illustration source.
- Preserve the subject identity and overall silhouette.
- Adapt the subject into a clean card illustration composition.

Card information:
- Card Name: "{CARD_NAME}"
- Element: "{ELEMENT}"
- Rarity: "{RARITY}"
- Project Name for card back: "{PROJECT_NAME}"

Language rule:
- All visible text on the card must be in English.

Front card layout:
- Top area: card name
- Center area: large main illustration
- Bottom area: element and 3 stats
- Include these stat labels: HP, ATK, DEF
- Do not include any skill description or effect text
- Optionally include the rarity label if it improves the composition

Back card layout:
- Show the project name as a text-based logo
- Use a clean decorative composition
- Use a thin frame matching the front card
- Keep the back minimal and visually elegant

Visual style:
- Inspired by cute minimal card designs
- Thin frame
- Soft but clean shapes
- Harmonious color palette
- Strong readability
- Slightly premium look
- Simple background with enough contrast
- No clutter
- No dense UI
- No complex gameplay text

Color rules:
- Choose the main colors based on the input character/item/logo and the selected element
- Keep the palette harmonious and readable
- Make sure the illustration stands out clearly from the background

Stat generation rules:
Generate HP, ATK, and DEF automatically using a 1–20 scale.
Base the values on rarity and visual impression.

Recommended ranges:
- Common: 4–9
- Rare: 8–14
- Epic: 13–20

Stat distribution guidance:
- Agile or offensive-looking subject: slightly higher ATK
- Tanky or defensive-looking subject: slightly higher HP or DEF
- Balanced-looking subject: more even distribution

Output composition:
- Show one clean flat presentation where the front and back are easy to inspect
- For the clear asset view, render both cards straight-on as flat isolated assets
- No drop shadow, no cast shadow, no glow, no perspective, no mockup surface, and no environmental lighting in the clear asset view
- Place the clear asset view on a plain solid background with strong contrast and clean sharp edges so the cards are easy to background-remove and reuse in design software
- Also show one separate portfolio mockup version with a more attractive presentation and slight perspective
- Keep everything visually cohesive as one mini card design project

Important constraints:
- Do not add skill effect descriptions
- Do not create a full gameplay system
- Do not overload the card with text
- The clear asset view must be production-ready for background removal
- Do not add any shadow around or underneath the cards in the clear asset view
- Focus on presentation quality, charm, clarity, and consistency
```

---

## Prompt rút gọn (dễ copy nhanh)

```text
Create a polished portfolio-quality game card concept based on the provided input image. The style should be cute, minimal, clean, modern, and slightly premium.

Generate a complete presentation including:
- a clear front card view,
- a clear back card view,
- and a portfolio mockup showing both.

Use the provided image as the main illustration source and preserve the subject identity.

Card info:
- Name: "{CARD_NAME}"
- Element: "{ELEMENT}"
- Rarity: "{RARITY}"
- Project Name: "{PROJECT_NAME}"

Front card:
- top: card name
- center: large illustration
- bottom: element + HP / ATK / DEF
- no skill description

Back card:
- text logo using the project name
- minimal decorative design
- thin frame matching the front

Clear asset view requirements:
- flat straight-on view
- no shadows
- no glow
- no perspective
- no mockup surface
- isolated on a plain solid background
- sharp clean edges for easy background removal

All text must be in English.
Choose colors based on the input subject and element. Keep the palette harmonious, readable, and visually cohesive.

Auto-generate stats on a 1–20 scale:
- Common: 4–9
- Rare: 8–14
- Epic: 13–20
Adjust the distribution based on the subject’s visual impression.
```

---

## Add-on để tránh shadow ở front/back
Nếu công cụ tạo ảnh hay tự thêm bóng đổ vào thẻ, hãy thêm đoạn này vào prompt:

```text
For the clear front-and-back card view, render both cards as flat, isolated assets with no drop shadow, no cast shadow, no glow, no perspective, no mockup surface, and no environmental lighting.

Place the cards on a plain solid background with clean, sharp edges so they can be easily background-removed and reused in design software.

Do not add any shadow around or underneath the cards.
```

Phiên bản ngắn:

```text
For the clear card asset view: no shadows, no glow, no perspective, no depth, no mockup, flat straight-on view, isolated on a plain solid background, sharp clean edges, easy to remove background.
```

---

## Ví dụ điền sẵn – Pyrokin

```text
Create a polished portfolio-quality game card concept based on the provided input image.

The card style should be cute, minimal, clean, modern, and more refined than a simple casual card game. The design should feel professional and visually cohesive, suitable for a designer portfolio.

Generate a complete card presentation that includes:
1. a clear front view of the card,
2. a clear back view of the card,
3. a polished portfolio mockup presentation showing both front and back.

Use the provided monster image as the main illustration source. Preserve the subject identity, proportions, and recognizable silhouette. Adapt it into a clean and charming card illustration composition.

Card information:
- Card Name: "Pyrokin"
- Element: "Fire"
- Rarity: "Common"
- Project Name for card back: "Ember Archive"

All visible text on the card must be in English.

Front card layout:
- Top area: "Pyrokin"
- Center area: large monster illustration
- Bottom area: element and 3 stats
- Include these stat labels: HP, ATK, DEF
- Do not include skill description text

Back card layout:
- Show "Ember Archive" as a text-based logo
- Use a thin frame and a clean decorative composition matching the front

Visual style:
- Cute, minimal, polished
- Thin frame
- Harmonious fiery palette
- Orange, ember, warm red, and subtle cream tones
- Soft premium feel
- Simple background
- Strong contrast and readability

Generate HP, ATK, and DEF automatically using a 1–20 scale.
For Common rarity, use the 4–9 range. Since the monster looks agile and offensive, slightly favor ATK over DEF.

Show:
- one clear flat front-and-back presentation
- one portfolio mockup version with slight perspective

Do not add skill effect descriptions.
Focus on charm, clarity, and presentation quality.
```

---

## Gợi ý khi dùng với công cụ tạo ảnh
- Nếu công cụ cho phép **upload ảnh tham chiếu**, hãy luôn upload ảnh monster/item/logo.
- Nếu công cụ hỗ trợ **nhiều ảnh đầu ra**, bạn có thể yêu cầu:
  - 1 ảnh **clear view**
  - 1 ảnh **mockup view**
- Nếu công cụ chỉ tạo **1 ảnh**, hãy yêu cầu nó đặt **front + back trong cùng một khung hình**.

---

## Gợi ý nâng cấp sau này
Bạn có thể mở rộng prompt này thêm các biến như:
- card type: Monster / Item / Resource / Logo
- border color by element
- rarity badge style
- alternate background patterns
- multiple cards in one set for a portfolio series

