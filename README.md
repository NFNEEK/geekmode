# GeekMode Next.js Template

A modern, feature-rich Next.js template for building scalable applications.

## 🚀 Features

- ⚡️ Next.js 15 with App Router
- 💎 TypeScript
- 🎨 Tailwind CSS
- 🔥 Shadcn/ui Components
- 🛠 Complete ESLint & Prettier Setup
- 📱 Responsive by Default
- 🌙 Dark Mode Support
- 🚄 GitHub Codespaces Ready

## 📦 Getting Started

### Using GitHub Templates

1. Click the "Use this template" button above
2. Choose "Create a new repository"
3. Select the owner and name for your new repository
4. Choose public or private visibility
5. Click "Create repository from template"

### Using GitHub Codespaces

1. Click the "Code" button above
2. Select the "Codespaces" tab
3. Click "Create codespace on main"

### Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🔧 Configuration

### Environment Variables

Copy `.env.example` to `.env.local`:

```bash
cp .env.example .env.local
```

### GitHub Features Used

- **Template Repository**: Easily create new projects
- **Codespaces**: Development environment in the browser
- **Actions**: Automated workflows
- **Dependabot**: Automated dependency updates
- **Issues Templates**: Standardized issue reporting
- **Project Boards**: Project management
- **Branch Protection**: Code quality assurance

## 🤝 Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## 📝 License

MIT License - feel free to use this template for any project!

---

# Template Usage Guide

## Using GitHub Features

### 1. Template Repository Setup
- Go to repository settings
- Enable "Template repository" under Settings > General
- Configure branch protection rules
- Set up required status checks

### 2. GitHub Actions
All workflows are in `.github/workflows/`:
- `template-validation.yml`: Validates template integrity
- `dependency-review.yml`: Reviews dependencies
- `codespace-prebuild.yml`: Prebuilds Codespaces

### 3. Codespaces Configuration
- Uses `.devcontainer/devcontainer.json`
- Preinstalled extensions
- Automated setup
- Port forwarding
- Environment variables

### 4. Issue Templates
Located in `.github/ISSUE_TEMPLATE/`:
- Bug report template
- Feature request template
- Custom templates as needed

### 5. Dependabot
Configuration in `.github/dependabot.yml`:
- Automated dependency updates
- Security updates
- Custom update schedule

### 6. Branch Protection
Recommended rules:
- Require pull request reviews
- Require status checks
- Require linear history
- No force pushes

## Best Practices

### Template Maintenance
1. Regular dependency updates
2. Security patches
3. Documentation updates
4. Feature additions
5. Community feedback

### Version Control
- Semantic versioning
- Changelog maintenance
- Release tags
- Release notes

### Security
- Security policy
- Code scanning
- Dependency review
- Secret scanning

## Quick Start Scripts

```bash
# Setup new project from template
gh repo create my-project --template yourusername/geekmode-nextjs-template

# Open in Codespaces
gh codespace create -r my-project

# Create new branch
git checkout -b feature/new-feature

# Update dependencies
npm update

# Run checks
npm run lint
npm run type-check
npm run build
```

## Directory Structure

```
.
├── .github/              # GitHub configuration
├── .devcontainer/        # Codespace configuration
├── app/                  # Next.js app directory
├── components/          # React components
├── lib/                # Utility functions
├── styles/            # Global styles
├── public/            # Static assets
└── types/             # TypeScript types
```# geekmode
