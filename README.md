<div align="center">
<sub>

English • [Català](locales/ca/README.md) • [Deutsch](locales/de/README.md) • [Español](locales/es/README.md) • [Français](locales/fr/README.md) • [हिन्दी](locales/hi/README.md) • [Italiano](locales/it/README.md)

</sub>
<sub>

[日本語](locales/ja/README.md) • [한국어](locales/ko/README.md) • [Polski](locales/pl/README.md) • [Português (BR)](locales/pt-BR/README.md) • [Türkçe](locales/tr/README.md) • [Tiếng Việt](locales/vi/README.md) • [简体中文](locales/zh-CN/README.md) • [繁體中文](locales/zh-TW/README.md)

</sub>
</div>
<br>

<div align="center">
  <h2>Join the Community</h2>
  <p>Connect with developers, contribute ideas, and stay ahead with the latest AI-powered coding tools.</p>

  <!-- Community links removed -->

</div>
<br>
<br>

<div align="center">
<h1>Xapian Coder</h1>

<!-- Marketplace and review links removed -->
<a href="https://github.com/YourUsername/YourRepoName/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop" target="_blank"><img src="https://img.shields.io/badge/Feature%20Requests-yellow?style=for-the-badge" alt="Feature Requests"></a>
<!-- Documentation link removed -->

</div>

**Xapian Coder** is an AI-powered **autonomous coding agent** that lives in your editor. It can:

- Communicate in natural language
- Read and write files directly in your workspace
- Run terminal commands
- Automate browser actions
- Integrate with any OpenAI-compatible or custom API/model
- Adapt its “personality” and capabilities through **Custom Modes**

Whether you’re seeking a flexible coding partner, a system architect, or specialized roles like a QA engineer or product manager, the Xapian Coder can help you build software more efficiently.

Check out the [CHANGELOG](CHANGELOG.md) for detailed updates and fixes.

---

## 🎉 Version 3.10 Released

Version 3.10 brings powerful productivity enhancements!

- Suggested responses to questions to save you time typing
- Improved large file handling through mapping out the file structure and reading only the relevant content
- Rebuilt @-mention file lookup that respects .gitignore and doesn't have a limit on the number of files tracked

---

## What Can This Xapian Coder Do?

- 🚀 **Generate Code** from natural language descriptions
- 🔧 **Refactor & Debug** existing code
- 📝 **Write & Update** documentation
- 🤔 **Answer Questions** about your codebase
- 🔄 **Automate** repetitive tasks
- 🏗️ **Create** new files and projects

## Quick Start

1. [Install the Xapian Coder](https://docs.example.com/getting-started/installing) <!-- Placeholder Link -->
2. [Connect Your AI Provider](https://docs.example.com/getting-started/connecting-api-provider) <!-- Placeholder Link -->
3. [Try Your First Task](https://docs.example.com/getting-started/your-first-task) <!-- Placeholder Link -->

## Key Features

### Multiple Modes

The Xapian Coder adapts to your needs with specialized [modes](https://docs.example.com/basic-usage/using-modes): <!-- Placeholder Link -->

- **Code Mode:** For general-purpose coding tasks
- **Architect Mode:** For planning and technical leadership
- **Ask Mode:** For answering questions and providing information
- **Debug Mode:** For systematic problem diagnosis
- **[Custom Modes](https://docs.example.com/advanced-usage/custom-modes):** Create unlimited specialized personas for security auditing, performance optimization, documentation, or any other task <!-- Placeholder Link -->

### Smart Tools

The Xapian Coder comes with powerful [tools](https://docs.example.com/basic-usage/how-tools-work) that can: <!-- Placeholder Link -->

- Read and write files in your project
- Execute commands in your VS Code terminal
- Control a web browser
- Use external tools via [MCP (Model Context Protocol)](https://docs.example.com/advanced-usage/mcp) <!-- Placeholder Link -->

MCP extends the Xapian Coder's capabilities by allowing you to add unlimited custom tools. Integrate with external APIs, connect to databases, or create specialized development tools - MCP provides the framework to expand the Xapian Coder's functionality to meet your specific needs.

### Customization

Make the Xapian Coder work your way with:

- [Custom Instructions](https://docs.example.com/advanced-usage/custom-instructions) for personalized behavior <!-- Placeholder Link -->
- [Custom Modes](https://docs.example.com/advanced-usage/custom-modes) for specialized tasks <!-- Placeholder Link -->
- [Local Models](https://docs.example.com/advanced-usage/local-models) for offline use <!-- Placeholder Link -->
- [Auto-Approval Settings](https://docs.example.com/advanced-usage/auto-approving-actions) for faster workflows <!-- Placeholder Link -->

## Resources

### Documentation

- [Basic Usage Guide](https://docs.example.com/basic-usage/the-chat-interface) <!-- Placeholder Link -->
- [Advanced Features](https://docs.example.com/advanced-usage/auto-approving-actions) <!-- Placeholder Link -->
- [Frequently Asked Questions](https://docs.example.com/faq) <!-- Placeholder Link -->

### Community

- **Discord:** [Join our Discord server](https://discord.gg/your-discord) for real-time help and discussions <!-- Placeholder Link -->
- **Reddit:** [Visit our subreddit](https://www.reddit.com/r/YourSubreddit) to share experiences and tips <!-- Placeholder Link -->
- **GitHub:** Report [issues](https://github.com/YourUsername/YourRepoName/issues) or request [features](https://github.com/YourUsername/YourRepoName/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop) <!-- Placeholder Link -->

---

## Local Setup & Development

1. **Clone** the repo:

```sh
git clone https://github.com/YourUsername/YourRepoName.git
```

2. **Install dependencies**:

```sh
npm run install:all
```

3. **Start the webview (Vite/React app with HMR)**:

```sh
npm run dev
```

4. **Debug**:
   Press `F5` (or **Run** → **Start Debugging**) in VSCode to open a new session with the Xapian Coder loaded.

Changes to the webview will appear immediately. Changes to the core extension will require a restart of the extension host.

Alternatively you can build a .vsix and install it directly in VSCode:

```sh
npm run build
```

A `.vsix` file will appear in the `bin/` directory which can be installed with:

```sh
code --install-extension bin/code-agent-<version>.vsix
```

We use [changesets](https://github.com/changesets/changesets) for versioning and publishing. Check our `CHANGELOG.md` for release notes.

---

## Disclaimer

**Please note** that The Project Maintainers do **not** make any representations or warranties regarding any code, models, or other tools provided or made available in connection with the Xapian Coder, any associated third-party tools, or any resulting outputs. You assume **all risks** associated with the use of any such tools or outputs; such tools are provided on an **"AS IS"** and **"AS AVAILABLE"** basis. Such risks may include, without limitation, intellectual property infringement, cyber vulnerabilities or attacks, bias, inaccuracies, errors, defects, viruses, downtime, property loss or damage, and/or personal injury. You are solely responsible for your use of any such tools or outputs (including, without limitation, the legality, appropriateness, and results thereof).

---

## Contributing

We love community contributions! Get started by reading our [CONTRIBUTING.md](CONTRIBUTING.md).

---

<!-- Contributors section removed -->

## License

[Apache 2.0 © 2025 The Project Maintainers](./LICENSE) <!-- Updated Year and Holder -->

---

**Enjoy the Xapian Coder!** Whether you keep it on a short leash or let it roam autonomously, we can’t wait to see what you build. If you have questions or feature ideas, check out our community channels. Happy coding!
