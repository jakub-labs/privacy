# Project preferences

This repository is the user's shared reference for reusable agent skills across projects. Consult its `.agents/skills/` catalog when available and read the relevant `SKILL.md` before applying a workflow. Apply skills when they fit the task; do not run unrelated workflows or install their optional tooling without a need.

At the start of each new project, check whether `jakub-labs/privacy` is already accessible as a shared skill reference. If it is not, prompt the user once to attach the repository or provide an authorized local checkout path. Do not request credentials in chat. Continue independent project work while access is pending. If access is already available, use it without asking again. Follow the active project's instructions and apply only relevant skills.

Use the Ponytail approach: prefer existing code, standard libraries, and native platform features; implement the smallest complete solution and verify it. Preserve safeguards, error handling, and explicit user requirements.

Instructions in the active project's repository and the user's current request take precedence over this shared reference. Do not copy skills or alter other projects merely to establish this preference.

For Windows optimization: begin with read-only diagnostics and present findings. Obtain explicit approval before system or registry changes. Back up registry, service, and power-plan settings before changing them. Apply changes incrementally and compare repeatable measurements; retain normal functionality and stability. AI use is the primary workload, with Rainbow Six Siege as the gaming target. Start with stock hardware settings; consider hardware tuning separately. Measure Defender's impact before proposing changes to its protection.

Cloud tasks already have isolated checkouts. Use the existing checkout; do not create a Git worktree unless the user explicitly requests one.
