# Heretic Git Guidelines

Heretic Git Guidelines (HGG) is a nonconformist Git management guide focusing on flexibility and simplicity for a rapid workflow.

---

## Purpose

Unlike typical Git guidelines that emphasize best practices with strict rules, this guideline prioritizes flexibility to simplify Git usage, allowing the user to focus more on the project.

#### What It Means

While other best practice guides are designed for public repositories with strict rules, HGG mainly focuses on using Git loosely to store projects in a snapshot manner.

For example, imagine you've made a stack of commits, but then you notice a single-word typo several commits ago. Fixing it requires either writing a long commit title filled with one-character diffs or rebasing the last few commits to amend your fix. Both options are equally messy.

Or, when the project is barely finished and you've built a lot of things from the ground up, using micro commits can easily clutter the history. Sometimes, all you need is just a saved checkpoint snapshot of your work.

---

## Guidelines

+ ### Main

	Trust the latest HEAD on the main branch as the most updated stable code. Focus on the current state of the codebase and ignore the commit history.

+ ### Branch

	Branches can be used for experimental or versioning reasons. They provide a sandbox for trying out new features or maintaining different versions of the codebase.

+ ### Commit

	Commit messages can be simple or detailed, but the primary goal is to capture the state of the project at a given moment. Clarity helps but not mandatory.

+ ### Tags

	Tags are used to mark points of interest in the snapshot history. They are reorderable and sorted by time. Tags can mark when a feature started to work, indicate a to-be-deleted algorithm, highlight other significant events in the project's timeline, etc.

---

## Usage

Mention in the project that it uses Heretic Git Guidelines.