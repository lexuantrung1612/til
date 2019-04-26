1. Empty commit
git commit --allow-empty -m "Trigger notification"
2. Search <partten> committed code in the git history
git rev-list --all | xargs git grep <expression>
