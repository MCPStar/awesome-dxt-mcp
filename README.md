# Awesome DXT MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <h3>🚀 A curated list of awesome Desktop Extensions (DXT) and MCP servers for Claude Desktop</h3>
  <p>
    <strong>Discover, share, and contribute to the growing ecosystem of AI-powered local tools and automations</strong>
  </p>
  
  [![GitHub stars](https://img.shields.io/github/stars/MCPStar/awesome-dxt-mcp?style=social)](https://github.com/MCPStar/awesome-dxt-mcp/stargazers)
  [![GitHub forks](https://img.shields.io/github/forks/MCPStar/awesome-dxt-mcp?style=social)](https://github.com/MCPStar/awesome-dxt-mcp/network/members)
  [![Contributors](https://img.shields.io/github/contributors/MCPStar/awesome-dxt-mcp)](https://github.com/MCPStar/awesome-dxt-mcp/graphs/contributors)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
</div>

---

## 📋 Table of Contents

- [What is DXT & MCP?](#what-is-dxt--mcp)
- [Getting Started](#getting-started)
- [Official Examples](#official-examples)
- [Community Extensions](#community-extensions)
- [Educational Resources](#educational-resources)
- [Development Tools](#development-tools)
- [Contributing](#contributing)
- [Community](#community)
- [License](#license)

---

## 🤔 What is DXT & MCP?

**Desktop Extensions (DXT)** are a packaging format introduced by Anthropic in June 2025 that makes installing MCP servers as simple as clicking a button. They bundle entire MCP servers with all dependencies into a single `.dxt` file.

**Model Context Protocol (MCP)** is an open-source protocol that enables AI applications like Claude Desktop to securely connect with local and remote resources.

### Key Benefits:
- ✅ **One-click installation** - No terminal or developer tools required
- 🔒 **Secure by design** - Sensitive data stays in OS keychain
- 🔄 **Automatic updates** - Extensions update seamlessly
- 🎯 **Local-first** - Your data never leaves your machine
- 🛠️ **Cross-platform** - Works on Windows, macOS, and Linux
- 📦 **Dependency-free** - All requirements bundled together

---

## 🚀 Getting Started

### For Users
1. **Download Claude Desktop** - Get the latest version from [claude.ai](https://claude.ai/download)
2. **Browse Extensions** - Find extensions in this list or Claude's built-in directory
3. **Install with One Click** - Download `.dxt` files and double-click to install
4. **Configure & Use** - Follow the setup prompts and start automating

### For Developers
```bash
# Install the official DXT CLI
npm install -g @anthropic-ai/dxt

# Initialize a new extension
dxt init

# Package your extension
dxt pack

# Validate your extension
dxt validate
```

---

## 🏢 Official Examples

> Reference implementations by Anthropic (⚠️ **Not production ready** - for learning purposes only)

| Name | Type | Description | Repository |
|------|------|-------------|------------|
| Hello World (Node.js) | Node.js | Basic MCP server with simple time tool | [anthropics/dxt](https://github.com/anthropics/dxt/tree/main/examples/hello-world-node) |
| Chrome AppleScript | Node.js | Browser automation via AppleScript | [anthropics/dxt](https://github.com/anthropics/dxt/tree/main/examples/chrome-applescript) |
| File Manager (Python) | Python | File system operations and path handling | [anthropics/dxt](https://github.com/anthropics/dxt/tree/main/examples/file-manager-python) |

**Note**: These examples demonstrate the DXT format but are **not intended for production use**. Use them as starting points for your own extensions.

---

## 🌱 Community Extensions

> Extensions built by the community - The ecosystem is growing! 

**🚧 Early Stage Notice**: Desktop Extensions are brand new (launched June 2025). Most available extensions are currently examples, prototypes, or early-stage projects. We're excited to see the ecosystem grow and mature!

### 📂 Current Status
- **Official Examples**: 3 reference implementations by Anthropic
- **Community Extensions**: *Looking for contributions!*
- **In Development**: Several projects in progress

### 🔍 Extension Categories

We're actively seeking community contributions in these areas:

#### 🛠️ Development Tools
*Help developers be more productive with Claude Desktop*
- Git integration and code review tools
- IDE connectors (VS Code, JetBrains, etc.)
- Docker and container management
- API testing and debugging tools

#### 💼 Productivity Tools
*Enhance daily workflows and task management*
- Calendar and scheduling assistants
- Note-taking and knowledge management
- Email automation and filtering
- Task and project management

#### 📁 File Management
*Organize and work with local files*
- Intelligent file organization
- Document search and indexing
- Backup and sync tools
- Media file processors

#### 🔗 API Integrations
*Connect Claude to external services*
- GitHub, GitLab, Bitbucket integration
- Slack, Discord, Teams connectors
- Notion, Obsidian, Roam databases
- Cloud storage services

#### 🗄️ Database Tools
*Work with databases and data sources*
- PostgreSQL, MySQL, SQLite connectors
- MongoDB and NoSQL databases
- Data visualization and analysis
- Query builders and executors

---

## 📚 Educational Resources

### Official Documentation
- [DXT Specification](https://github.com/anthropics/dxt/blob/main/README.md) - Complete technical specification
- [Manifest Documentation](https://github.com/anthropics/dxt/blob/main/MANIFEST.md) - Extension manifest reference
- [Official Examples](https://github.com/anthropics/dxt/tree/main/examples) - Reference implementations

### Community Resources
*Looking for community-created tutorials, guides, and examples!*

---

## 🧰 Development Tools

### Official SDKs

| Name | Description | Language | Repository |
|------|-------------|----------|------------|
| DXT CLI | Official development toolkit | TypeScript | [anthropics/dxt](https://github.com/anthropics/dxt) |
| MCP SDK Node.js | Node.js SDK for MCP | JavaScript | [modelcontextprotocol/node-sdk](https://github.com/modelcontextprotocol/node-sdk) |
| MCP SDK Python | Python SDK for MCP | Python | [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) |

### Development Workflow

```bash
# Install the official DXT CLI
npm install -g @anthropic-ai/dxt

# Initialize a new extension
dxt init --template node  # or python, binary

# Development workflow
dxt pack    # Create .dxt package
dxt validate # Validate manifest and package
```

---

## 🤝 Contributing

**🌟 Be a Pioneer!** Desktop Extensions are brand new (June 2025), and we need your help building this ecosystem from the ground up.

### 🚀 Ways to Contribute

#### 📦 Build Extensions
- **Start simple** - Even basic file tools are valuable
- **Share early** - Prototypes and experiments welcome
- **Document thoroughly** - Help others learn from your work

#### 📝 Improve Documentation
- Add tutorials and guides
- Create video walkthroughs  
- Share best practices and patterns

#### 🔍 Curate Content
- Find and evaluate new extensions
- Test extensions on different platforms
- Report bugs and compatibility issues

### 📋 Submission Guidelines

#### ✅ What We Accept
- **Working prototypes** - Even if basic, if it works it counts!
- **Educational examples** - Beyond the official ones
- **Experimental tools** - Trying new ideas and concepts
- **Learning resources** - Tutorials, guides, videos

#### 📝 How to Submit

1. **Fork this repository**
2. **Add your extension** using this format:
   ```markdown
   | [Extension Name](repo-url) | Brief description | Platform | Language | Status |
   ```
3. **Submit a pull request** with clear description

#### 🏷️ Status Labels
- 🚧 **Prototype** - Basic functionality, may have limitations
- 🔬 **Experimental** - Testing new concepts or approaches  
- 📚 **Educational** - For learning DXT/MCP development
- ⚠️ **Alpha** - Early version, expect bugs
- ✅ **Stable** - Ready for daily use

### 💡 Extension Ideas for Beginners

**Quick Wins** (1-2 hours):
- Current time/date display tool
- Simple text file reader
- Basic system info reporter
- Random quote generator

**Weekend Projects** (1-2 days):
- File size analyzer
- Text search in directory
- Basic calculator with history
- Simple note-taking tool

Read our full [Contributing Guide](CONTRIBUTING.md) for detailed guidelines.

---

## 🌟 Community

### 💬 Join the Discussion
- [GitHub Discussions](https://github.com/MCPStar/awesome-dxt-mcp/discussions) - Questions and ideas
- [GitHub Issues](https://github.com/MCPStar/awesome-dxt-mcp/issues) - Bug reports and suggestions

### 📢 Stay Connected
- ⭐ **Star this repo** to show support and stay updated
- 👀 **Watch releases** for new additions

### 🏆 Contributors

Thanks to all our amazing contributors!

<a href="https://github.com/MCPStar/awesome-dxt-mcp/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MCPStar/awesome-dxt-mcp" alt="Contributors" />
</a>

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The extensions listed in this repository are licensed under their respective licenses as indicated in each entry.

---

## 🙏 Acknowledgments

- **Anthropic Team** for creating Claude Desktop and the DXT specification
- **MCP Community** for building the foundation protocol
- **All Extension Developers** for creating amazing tools

---

<div align="center">
  <p>
    <strong>🚀 Ready to build the future of AI extensions?</strong>
  </p>
  <p>
    <a href="https://github.com/anthropics/dxt">Get Started with DXT</a> •
    <a href="CONTRIBUTING.md">Contribute to this List</a> •
    <a href="#awesome-dxt-mcp-">Back to Top ↑</a>
  </p>
</div>