# CLAUDE.md

> **Note**: This is a personal knowledge documentation repository for storing notes and learnings.

## Repository Purpose

This repository is designed for documenting personal knowledge, notes, and learnings. It uses Git for version control to track changes and maintain history of all documentation.

## Common Commands

```bash
# View status of changes
git status

# Add new or modified files
git add <filename>
# or add all changes
git add .

# Commit changes with a message
git commit -m "Description of changes"

# Push changes to remote
git push

# Pull latest changes
git pull

# View commit history
git log

# Search through notes
git grep "search term"
```

## Project Structure

```
.
├── .git/                    # Git repository
├── .keep                    # Placeholder file
├── AI_READINESS_AUDIT.md    # Comprehensive AI readiness assessment
├── CLAUDE.md                # This file - development documentation
└── README.md                # Project overview and usage guide
```

As you add more notes, organize them in subdirectories by topic:
- Create folders for different knowledge areas
- Use markdown (.md) files for documentation
- Keep related notes together

## Documentation Style

Best practices for maintaining notes in this repository:

- **Use Markdown**: All notes should be in markdown format (.md files)
- **Clear Headers**: Use descriptive headers to organize content
- **Consistent Naming**: Use lowercase with hyphens for filenames (e.g., `my-topic-notes.md`)
- **Linking**: Use relative links to reference other notes in the repository
- **Code Blocks**: Use fenced code blocks with language specification for code snippets
- **Commit Messages**: Write clear commit messages describing what was added/changed

## Organization Tips

- Create a table of contents file if the repository grows large
- Use subdirectories to group related topics
- Add dates to time-sensitive information
- Include sources/references for external information
- Tag or categorize notes for easier searching
