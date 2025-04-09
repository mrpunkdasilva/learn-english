# Learn English Documentation Project

A comprehensive English learning documentation project built with Writerside, focusing on grammar fundamentals, vocabulary, and practical usage.

## 📚 Project Structure

```
.
├── Writerside/
│   ├── topics/           # Markdown content files
│   ├── images/           # Image assets
│   ├── cfg/              # Configuration files
│   ├── in.tree          # Navigation structure
│   └── writerside.cfg   # Main configuration
├── docs/                 # Generated HTML documentation
└── scripts/             # Automation scripts
```

## 🎯 Content Categories

### 1. Grammar Fundamentals
- Verbs and conjugations
- Plural nouns
- Adjectives and adverbs
- There is/are constructions
- WH questions

### 2. Modal Verbs
- Must vs Should
- May, Could, Can comparisons

### 3. Comparisons
- Comparative forms
- Superlative forms

### 4. Practical Usage
- Greetings
- At a cafe
- Sports conversations
- Simple vocabulary

## 🛠 Technical Setup

### Prerequisites
- JetBrains Writerside
- Git
- Bash (for running scripts)

### Build and Deploy

1. Build documentation:
```bash
# Use Writerside to build the project
```

2. Deploy changes:
```bash
./scripts/main.sh
```

This will:
- Unzip Writerside content
- Push changes to remote repository

## 🔄 Automation

The project includes several automation scripts:

- `push_remote_repo.sh`: Automatically commits and pushes changes
- `unzip_writerside.sh`: Handles Writerside content extraction
- `main.sh`: Main orchestration script

## 🎨 Customization

The project appearance is customized through:
- Primary color: #E8488B
- Custom CSS: custom.css
- Logo: images/logo-primary.svg

## 📖 Documentation Structure

The documentation is organized in a hierarchical structure defined in `in.tree`:
- Grammar fundamentals at the top level
- Progressive complexity in topic presentation
- Cross-referenced content for better navigation

## 🔍 Search Configuration

Search functionality is configured with:
- Maximum hits: 75
- Color preset: contrast
- Custom indexing rules

## 👥 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 Content Guidelines

When adding new content:
1. Use clear, concise explanations
2. Include practical examples
3. Add relevant images when helpful
4. Follow the existing markdown structure
5. Cross-reference related topics

## 🚀 Deployment

The documentation is automatically built and deployed when changes are pushed to the main branch.

## 📄 License

Copyright PunkDomus 2025

## 🤝 Contact

For questions or suggestions, please open an issue in the repository.

## 🔮 Future Plans

- Add audio pronunciation guides
- Expand vocabulary sections
- Include interactive exercises
- Add more real-world conversation examples
- Implement progress tracking

## 🏗 Project Status

Active development - Regular updates and content additions.