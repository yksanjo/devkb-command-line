# DevKB CLI - Developer Knowledge Base (CLI Edition)

A terminal-based knowledge management system for developers to index and query their codebase.

## Features

- **Index** - Index codebase files for searching
- **Search** - Search indexed files
- **Ask** - Ask questions about your codebase
- **Add** - Add knowledge entries
- **List** - List all knowledge entries
- **Stats** - Show statistics

## Installation

```bash
npm install -g @devkb/cli
```

## Usage

```bash
# Initialize DevKB in your project
devkb init

# Index your codebase
devkb index

# Search for files
devkb search "auth"

# Ask a question
devkb ask "how do we handle authentication?"

# Add a knowledge entry
devkb add decision --title "Chose JWT for auth" --content "..." --tags auth,jwt

# List all entries
devkb list

# Show statistics
devkb stats
```

## License

MIT
