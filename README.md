# zendriix-gitflow
echo "# Zendriix Gitflow

This repository simulates a Gitflow branching model for monthly product releases at Zendriix Softwares.

## Branch Strategy

- master: Production-ready code (monthly release on 25th)
- develop: Integration of all features
- feature/*: Feature development
- release/*: Pre-release testing and fixes
- hotfix/*: Urgent production fixes
" > README.md

git add README.md
git commit -m "Add README describing Gitflow strategy"
git push
