# BADM 554 Team Project Repository

This is your team's shared repository for the BADM 554 project. It was created for you in the course organization during Week 1 Project Studio. It is **private for the term**: your team, the instructor, and the course mentors can see it. Nobody else can.

This is the same repository your team submits from in Module 8, so everything your project produces eventually lives here.

## The one rule until Module 6

> **Until we learn branches, you commit only inside your own folder.**
> If you need to change a file in somebody else's folder or in `shared/`, ask them to do it.

Each teammate works inside their own directory under `members/`. This is not busywork: two people editing the same file is how merge conflicts happen, and we don't teach conflict resolution until Module 6. Work in your own folder and you will never see one before you're ready for it.

One habit goes with the rule: **Sync before you start, Sync when you stop.** (In VS Code, the Sync button in the Source Control panel pulls your teammates' work and pushes yours.)

## What goes where

| Folder | What it holds | Who writes there |
|---|---|---|
| `members/<your-netid>/` | Your own work in progress | Only you |
| `shared/` | Instructor-seeded starter files; team deliverables from Module 6 on | Read-only until Module 6 |
| `data/` | Local data files — **never committed** (gitignored) | Everyone, locally only |
| `docs/ai-attribution-log.md` | The **team** AI Attribution Log for shared deliverables, from Module 6 on. Individual assignments (Modules 1–5) log AI use in **Part C of the assignment notebook** instead | Everyone, own entries (from Module 6) |
| `README.md` | This file; later, your project README | The designated integrator only |

## If git ever gets into a state you don't understand

You are not stuck and you have not lost anything. Use the **Fresh Clone Rule** (see the course page): copy your changed files out, delete the folder, clone again, copy your files back in, commit and push. Experienced engineers do it too.

## What must never be committed

Credentials of any kind, personal data exports, or anything with another person's information in it. The `.gitignore` in this repo blocks the common cases, but the check is yours to make **before** the first commit — a private repo is not a safe place for secrets, and history is forever. Full guidance: the *Submitting with a GitHub Repo* course page.
