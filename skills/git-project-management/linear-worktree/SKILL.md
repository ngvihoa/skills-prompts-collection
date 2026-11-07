---
name: linear-worktree
description: Implement a Linear issue in an isolated Git worktree, validate the change, and prepare the requested commit, pull request, review, or QA handoff using the target repository's conventions.
---

# Linear issue in an isolated worktree

Input: a Linear issue ID or URL and the target repository. Determine the requested endpoint: local implementation, committed change, pull request, or reviewed handoff. Follow the user's scope and the repository's instructions; this skill does not grant additional permission to push, merge, update issues, release, or change shared data.

No company-specific agent, branch name, environment command, account, or QA owner is required. Discover the repository's equivalents and ask only when a necessary mapping cannot be established.

## Inspect the task and ownership

Read the issue, relevant parent/comments, acceptance criteria, existing subtasks, and linked work. Use an available authorized Linear integration. If it is unavailable, work from the issue details the user supplies and report that synchronization is unavailable.

Inspect Git status, branches, worktrees, and any existing PR for the task. Reuse task-owned work when ownership is clear; do not create a duplicate or overwrite another session. Preserve unrelated work. For concurrent runs, use a task claim mechanism supported by the environment; do not remove an unknown live claim.

## Create the worktree

Determine the remote and PR base from repository instructions, an existing task PR, or the remote default branch. Do not assume a fixed base such as a staging branch. Record its commit before branching. Choose an unused branch and worktree path following repository conventions.

Run edits, installs, builds, validation, and Git mutations inside the owned worktree. Do not switch, stash, clean, or reset the original checkout. Install dependencies using the package manager and lockfile in that repository; do not symlink another checkout's dependencies or generated output.

Prepare configuration using the project's documented process. Do not copy secrets or environment files from another checkout. Check the intended runtime/data environment without printing secret values. Stop environment-dependent work when its target cannot be verified.

## Implement and validate

Implement the acceptance criteria with focused changes. Use the repository's appropriate checks and review conventions. If an expected check cannot run, explain the limitation. Inspect the full diff, stage only task-owned changes when a commit is in scope, and exclude secrets, local progress notes, and unrelated edits.

Create commits, push the task branch without force, open/update a PR, and update the issue only when those actions are part of the authorized endpoint. Choose the discovered base and naming conventions. A request for implementation alone is not a request to merge or release.

## Review and handoff

When review is requested, inspect checks and findings for the latest PR head. A queued job or successful trigger is not proof of a completed review. Evaluate findings, fix valid in-scope issues, and record why a finding was rejected or deferred. Keep waits bounded and report repeated failures or unavailable prerequisites rather than looping indefinitely.

If QA handoff is part of the requested workflow, reuse a matching verification task where possible. Derive scenarios from acceptance criteria or bug reproduction: prerequisites, steps, expected results, deployment prerequisites, and evidence to collect. Resolve owners and workflow statuses from repository/team configuration; do not assign people or invent state mappings.

Report the worktree/branch, implementation, validation evidence and gaps, PR/review state, and any QA handoff. Distinguish implementation completion from review, deployment, and verified behavior. Preserve the worktree for follow-up unless cleanup is requested.
