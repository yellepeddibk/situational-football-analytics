# Contributing to Situational Football Analytics

## Branching Strategy
- Always create a new branch from `main` for your work
- Name branches descriptively (e.g. `feature/red-zone-analysis`)
- Never push directly to `main`

## Workflow
1. Create a new branch: `git checkout -b "branch-name"`
2. Make your changes
3. Stage and commit: `git add .` then `git commit -m "descriptive message"`
4. Push: `git push -u origin branch-name`
5. Open a Pull Request on GitHub from your branch → `main`

## Commit Messages
- Be descriptive and concise
- Use present tense (e.g. "Add red zone analysis" not "Added red zone analysis")

## Pull Requests
- Fill out the PR template fully
- Link any relevant issues
- Wait for review before merging
- Do not merge your own PR without review

## Data
- All data is publicly available Iowa State football play-by-play data
- Raw data files go in `data/raw/` — do not modify them
- Processed/cleaned data goes in `data/processed/`
- Do not delete or overwrite existing data files without team discussion

## Notebooks
- Clear notebook outputs before committing (Cell → Clear All Outputs)
- Use descriptive variable names and add comments where needed