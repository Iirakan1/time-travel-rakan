# Git Learning Journal

## What I Learned
Through this assignment, I gained hands-on experience with professional Git workflows including branching strategies, pull requests, and collaborative development. I learned how to use feature branches (author/idea-sprint and editor/review) to simulate Author and Editor roles, manage issues through GitHub CLI, and coordinate changes via pull requests. Understanding merge conflicts and how to resolve them improved my confidence in collaborative development.

## Two Mistakes I Fixed

**Mistake 1:** Initially tried to create branches before making any commits, which failed with "fatal: not a valid object name: 'master'". Fixed by committing initial files before creating feature branches.

**Mistake 2:** Created a merge conflict by editing the same lines (intro.md) on different branches without coordination. Resolved by manually editing the conflicted file to combine both the author and editor perspectives, demonstrating how Git's conflict markers help identify and resolve overlapping changes.

## Command That Saved the Day
`git merge` with manual conflict resolution. When I encountered the merge conflict, understanding how to carefully read Git's conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) and manually edit the file to keep both contributions saved the assignment. This taught me that conflicts aren't failures—they're opportunities to thoughtfully combine work.
