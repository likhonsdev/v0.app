<div align="center">

# V0.App - Turn Ideas into Real Web Apps 🚀

![Build Status](https://github.com/likhonsdev/v0.app/workflows/Next.js%20CI/CD/badge.svg)
![Deno Tests](https://github.com/likhonsdev/v0.app/workflows/Deno/badge.svg)
![Webpack Build](https://github.com/likhonsdev/v0.app/workflows/NodeJS%20with%20Webpack/badge.svg)
[![License](https://img.shields.io/github/license/likhonsdev/v0.app)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/likhonsdev/v0.app)](https://github.com/likhonsdev/v0.app/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/likhonsdev/v0.app)](https://github.com/likhonsdev/v0.app/issues)

<p align="center">
  <strong>An innovative platform that transforms your ideas into functional web applications using natural language - no coding required!</strong>
  <br />
  <br />
  Simply describe what you want, and v0's intelligent agent builds it using modern frontend tools.
  <br />
  <br />
  <a href="#-get-started"><strong>Get Started »</strong></a>
  <br />
  <br />
  <a href="https://github.com/likhonsdev/v0.app/issues/new?assignees=&labels=bug&projects=&template=bug_report.md&title=">Report Bug</a>
  ·
  <a href="https://github.com/likhonsdev/v0.app/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.md&title=">Request Feature</a>
  ·
  <a href="#-contact">Contact</a>
</p>

</div>

## ✨ Key Features

- 🗣 **Natural Language Interface** - Describe your app in plain English
- 🎨 **High-fidelity UI Generation** - Create UIs from wireframes or mockups
- 🔄 **Workflow Integration** - Add functionality through simple step descriptions
- 🚀 **One-Click Deploy** - Deploy to secure, scalable infrastructure
- 🔍 **Web Search & Inspection** - Search and analyze web content
- 🛠 **Automatic Error Fixing** - Intelligent diagnostics and fixes
- 🔌 **Tool Integration** - Connect with external tools and APIs

## 🛠 Technical Features

- ✅ **Next.js 15.3.2** with React 19 for modern frontend
- ✅ **Bun + Express** backend for high performance
- ✅ **Containerized applications** with Docker
- ✅ **Full-featured Monaco** code editor
- ✅ **Real-time chat assistant**
- ✅ **Live preview** with responsive design
- ✅ **Project export** and deployment capabilities

## 📋 Project Structure

```
v0.app/
├── frontend/           # Next.js frontend application
├── backend/           # TypeScript backend services
└── .github/
    └── workflows/     # CI/CD and automation workflows
```

## 🔧 CI/CD Workflows

### Next.js CI/CD (`nextjs.yml`)
- 🏗️ Builds and tests Next.js application
- 📦 Exports static site
- 🚀 Deploys to both GitHub Pages and Vercel
- ✨ Includes type checking and linting

### Webpack Build (`webpack.yml`)
- 🔨 Builds NodeJS projects
- ✅ Tests across Node versions (16.x, 18.x, 20.x)
- 📤 Uploads build artifacts

### Deno Testing (`deno.yml`)
- 🧪 Runs tests and generates coverage
- 📝 Verifies code formatting
- 🔍 Performs type checking
- 📊 Uploads coverage reports

### Repository Automation (`auto-activity.yml`)
- 📊 Tracks repository statistics
- 👥 Updates contributor graphs
- 🖼️ Generates social preview images
- 🤖 Auto-merges updates

## 🚀 Get Started

### Prerequisites

1. **Docker** - Install Docker Desktop or Docker Engine
   - [Docker Desktop for Mac](https://www.docker.com/products/docker-desktop/)
   - [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/)
   - [Docker Engine for Linux](https://docs.docker.com/engine/install/)

2. **API Key** - Get an API key from any OpenAI SDK compatible provider

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/likhonsdev/v0.app.git
   cd v0.app
   ```

2. **Configure API settings**
   
   Edit the `config.ts` file with your API configuration:
   ```typescript
   baseUrl: "https://openrouter.ai/api/v1",
   apiKey: "sk-...",
   model: "anthropic/claude-sonnet-4",
   temperature: 0.7,
   ```
   
   > 💡 **Recommendation**: Use Anthropic's Claude Sonnet-4 for best coding results

3. **Start the application**
   ```bash
   sh start.sh
   ```

4. **Access the application**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend: [http://localhost:4000](http://localhost:4000)

### Development Commands

```bash
# Frontend development
cd frontend
npm install
npm run dev

# Run tests
npm test

# Type checking
npm run typecheck

# Linting
npm run lint
```

## 💡 Why Choose V0?

### For Teams
- **Product Managers** - Quickly prototype and validate ideas
- **Designers** - Turn mockups into real, high-fidelity UIs
- **Engineers** - Scaffold full-stack apps following best practices
- **Data Scientists** - Work with Python and SQL seamlessly
- **Marketing Teams** - Create custom landing pages quickly
- **Content Creators** - Build interactive examples and tutorials
- **Customer Support** - Develop support tools efficiently
- **Founders** - Ship MVPs fast without a large dev team

### Why Run Locally?

Building applications shouldn't require expensive subscriptions or sacrificing your privacy. V0 gives you the power of platforms like Loveable, Replit, and Bolt without the downsides:

- **🔒 Full Control & Privacy** - Your code never leaves your machine
- **💰 Your API Keys, Your Costs** - Pay only for what you use
- **🚫 No Limitations** - Complete feature access from day one
- **📴 Offline Capable** - Work without internet dependency
- **🔧 Customizable** - Modify the platform to fit your needs

> Most cloud-based AI platforms charge $20-100+ monthly while limiting usage. With V0, a $5 API credit can generate dozens of applications!

## 🛠 Technologies

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: TypeScript, Bun, Express, Deno
- **Build Tools**: Webpack, Gulp
- **Testing**: Jest, Testing Library
- **CI/CD**: GitHub Actions
- **Deployment**: Vercel, GitHub Pages
- **Containerization**: Docker

## 📝 Environment Variables

Required secrets for deployments:

- `VERCEL_TOKEN`
- `VERCEL_ORG_ID` 
- `VERCEL_PROJECT_ID`
- `WAKATIME_API_KEY` (optional)

## 🗺 Roadmap

- 🔄 LLM streaming support
- 🔄 Document & image attachments
- 🔄 Improved fault tolerance
- 🔄 Comprehensive test coverage
- 🔄 Multi-framework support (beyond Next.js)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please see our [Contributing Guide](CONTRIBUTING.md) for detailed guidelines.

## 📫 Contact

Have questions or want to chat about V0? We'd love to hear from you!

- 🌟 [GitHub Issues](https://github.com/likhonsdev/v0.app/issues) - Bug reports and feature requests
- 🐦 Follow [@likhonsdev](https://twitter.com/likhonsdev) for updates
- 📧 Email: contact@v0.app

## 🛡 Disclaimer

V0.App is an experimental application provided "as-is" without warranty. Users assume all risks associated with its use. The developers are not responsible for any losses, damages, or consequences resulting from the software's use.

**Important**: LLM usage can be expensive due to token consumption. Monitor your API usage regularly and set up limits to prevent unexpected charges.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

⭐️ **If you find this project useful, please consider giving it a star!**

**[⬆ Back to Top](#readme-top)**

</div>
