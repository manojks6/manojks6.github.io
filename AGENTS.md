# Manual Execution Only Rules

## Core Principle
You may read, analyze, search, and edit files.  
You may NOT execute tests, builds, package managers, shells, Git actions, migrations, servers, or scripts unless I explicitly ask.

## Forbidden Automatic Actions
Do not run:

### Tests / Builds
- npm test
- pnpm test
- yarn test
- pytest
- go test
- cargo test
- mvn test
- gradle test
- make
- npm run build
- pnpm build
- yarn build

### Package Managers
- npm install
- pnpm install
- yarn install
- pip install
- composer install

### Git Commands
- git status
- git add
- git commit
- git push
- git pull
- git fetch
- git merge
- git rebase
- git checkout
- git switch
- git reset
- git stash
- git tag
- git branch
- git cherry-pick
- git hooks

### Dev Tools / Runtime
- docker commands
- lint commands
- format commands
- dev servers
- database migrations
- any bash scripts
- any powershell scripts
- shell commands of any kind

## Required Workflow
1. Inspect relevant files only.
2. Make minimal code changes.
3. Explain what changed.
4. Tell me exactly what I should run manually to verify.

## If You Think Execution Is Needed
Ask first. Never assume permission.

## Output Format
- Files changed
- Summary of edits
- Manual test steps for me

## Cost Saving Rules
- Do not scan the whole repo.
- Read minimum files needed.
- Keep responses concise.
- Prefer one-pass fixes.

## Final Instruction
Never run commands. I will handle all terminal, Git, testing, and deployment steps manually.