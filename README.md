# MacBook Setup Guide

This comprehensive setup guide contains all the essential tools, applications, and configurations discovered on your current MacBook. Use this as a reference when setting up a new Mac.

# Note: Ignore versions.

## Development Tools & Languages

### Core Development
- **Node.js** (v22.18.0) - JavaScript runtime
- **npm** (v11.5.2) - Node package manager
- **Python** (v3.13.5) - Programming language
- **pip** (v25.2) - Python package manager
- **uv** - Fast Python package installer and resolver
- **uvicorn** - Lightning-fast ASGI server for Python web apps
- **Git** (v2.50.1) - Version control system
- **Docker** (v28.3.2) - Containerization platform

### Cloud CLI Tools
- **AWS CLI** (v2.28.1) - Amazon Web Services CLI
- **Google Cloud CLI** (v532.0.0) - Google Cloud Platform CLI
- **Azure CLI** (v2.76.0) - Microsoft Azure CLI
- **Terraform** (v1.12.2) - Infrastructure as Code
- **Kubectl** (v1.33.3) - Kubernetes CLI

### AI & Development Tools
- **Claude Code** (v1.0.70) - Anthropic's Claude CLI
- **Claude Code Router** - Claude Code Router for using different LLMs with Claude Code
- **Cursor CLI** - Cursor AI code editor command line tool
- **Ollama** (v0.11.3) - Local LLM runner
- **GitHub CLI** (v2.76.2) - GitHub command line tool
- **ChatGPT Desktop** - ChatGPT Desktop version with App access
- **Claude Desktop** - Claude Desktop version with MCP and App access

### Code Editors & IDEs
- **Cursor** - Primary AI-powered code editor (recommended)
  - Import settings from VSCode when setting up
- **Visual Studio Code** (v1.102.1) - Alternative code editor

## Package Managers & Version Managers

### Homebrew
- **Homebrew** (v4.6.0) - macOS package manager
- 42 total packages installed
- 3 cask applications installed

### Node Version Management
- **NVM** (v0.40.3) - Node Version Manager

### Python Version Management
- **pyenv** (v2.6.5) - Python Version Manager

## Key Homebrew Packages

### Development & DevOps
- awscli
- azure-cli
- gh (GitHub CLI)
- git
- kubernetes-cli
- minikube
- terraform
- node

### Databases
- mongodb-community@6.0
- mongodb-database-tools
- mongosh
- postgresql@15

### Utilities & Libraries
- curl
- brotli
- openssl@3
- ca-certificates
- gettext
- libssh2
- libuv
- pcre2

### Homebrew Casks
- gcloud-cli
- iterm2
- maccy

## Global NPM Packages

### Core Tools
- @anthropic-ai/claude-code@1.0.70
- corepack@0.33.0
- npm@11.5.2

## Applications

### Productivity & Communication
- **Notion** - All-in-one workspace for notes, tasks, and collaboration
- **Asana** - Project management and team collaboration
- **Loom** - Screen recording and video messaging
- **WhatsApp** - Messaging application
- **Zoom** - Video conferencing
- **Upwork** - Freelancing platform client

### Development Tools
- **Figma** - Design and prototyping tool
- **Postman** - API development and testing
- **MongoDB Compass** - MongoDB database GUI
- **Amazon Q** - AWS AI assistant
- **Grammarly Desktop** - Writing assistant

### System Utilities
- **Rectangle** - Window management tool
- **Caffeine** - Prevents system sleep
- **Maccy** - Clipboard manager (also via Homebrew)
- **iTerm** - Terminal emulator (also via Homebrew)
- **superwhisper** - Voice transcription tool
- **Wispr Flow** - Voice-to-text productivity tool
- **Cloudflare WARP** - VPN and DNS service
- **Blackmagic Proxy Generator Lite** - Video proxy generation

### Browsers & Web Tools
- **Google Chrome** - Web browser
- **Safari** - Default macOS web browser

### System & Container Tools
- **Docker** - Containerization platform (desktop app)
- **Ollama** - Local LLM runner (desktop app)

## Shell Configuration

### Zsh Setup (Primary Shell)
- **Oh My Zsh** - Zsh framework
- **Powerlevel10k** - Zsh theme
- **Plugins**: git, zsh-autosuggestions, zsh-syntax-highlighting, web-search

### Terminal Setup Tutorial
📹 **Video Guide**: [Complete Terminal Setup on New Mac](https://www.youtube.com/watch?v=CF1tMjvHDRA) - Comprehensive walkthrough for terminal configuration

### Key Aliases
```bash
alias python='python3'
alias pip='pip3'
```

### Environment Variables & PATH
- NVM configuration for Node.js
- pyenv configuration for Python
- Google Cloud SDK paths
- AWS CLI completion
- PostgreSQL paths
- Docker CLI completions
- Terraform completion

## Important Configuration Files

### Git Configuration
- User: Abdullah Khan
- Email: aabdullahkhan4@gmail.com
- Default branch: main

### Dotfiles Present
- `.zshrc` - Zsh configuration
- `.zprofile` - Zsh profile
- `.bashrc` - Bash configuration
- `.gitconfig` - Git configuration
- `.claude.json` - Claude Code configuration

## Additional Software Integrations

### Amazon Q Integration
- Shell integration configured in both zshrc and zprofile

### Docker Desktop
- CLI completions configured

### Google Cloud SDK
- Path and completion scripts sourced

## Development Directories Structure

```
~/
├── Repositories/
│   ├── client-work/
│   ├── learning/
│   └── production-ready-projects/
├── Documents/
├── Downloads/
└── Desktop/
```

## Important Notes

### Security Considerations
- Keep sensitive files like `.claude.json` and AWS credentials secure
- Review and backup configuration files regularly
- Use proper file permissions for SSH keys and config files

### Backup Recommendations
- Backup all dotfiles (`.zshrc`, `.gitconfig`, etc.)
- Export and backup package lists before migration
- Document custom configurations and aliases
- Save development environment settings

### Performance Tips
- Clean up old Node.js versions periodically with `nvm`
- Remove unused Python versions with `pyenv`
- Keep Homebrew updated: `brew update && brew upgrade`
- Regularly clean Docker images and containers

### Future Setup Considerations
- Version numbers may change - install latest stable versions
- Some packages may have different names in future Homebrew versions
- Review and update shell configurations as needed
- Verify all CLI tool authentications after fresh install

## Setup Priority Order

1. Install Homebrew
2. Install core development tools (Git, Node.js, Python)
3. Install version managers (NVM, pyenv)
4. Set up shell (Zsh, Oh My Zsh, Powerlevel10k)
5. Install cloud CLIs (AWS, GCP, Azure)
6. Configure development environment
7. Install additional tools and utilities
8. Restore configuration files and settings

---

*This setup guide was generated based on your current MacBook configuration as of August 2025*
