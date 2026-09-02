# 🚀 OmniRoute Setup Guide – Free AI Gateway in VS Code

A complete, step-by-step guide to install and use **OmniRoute** – the free AI gateway that gives you access to **1200+ AI models** (Claude, GPT, Gemini, DeepSeek, Kimi, GLM and more) directly inside **VS Code Copilot Chat** – **completely free**.

> Perfect for developers who want powerful AI assistance without subscription costs.

---

## 📖 Table of Contents
- [What is OmniRoute?](#what-is-omniroute)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dashboard Overview](#dashboard-overview)
- [Creating API Keys](#creating-api-keys)
- [VS Code Setup](#vs-code-setup)
- [Available Models](#available-models)
- [Daily Usage](#daily-usage)
- [Troubleshooting](#troubleshooting)
- [Tips & Tricks](#tips--tricks)
- [Support & Resources](#support--resources)

---

## 🤖 What is OmniRoute?

OmniRoute is a free, self-hosted AI gateway that:

- ✅ Aggregates **350+ AI providers** (150+ with free tiers)
- ✅ Gives access to **1200+ models** from OpenAI, Anthropic, Google, DeepSeek, Kimi, and more
- ✅ Works inside **VS Code Copilot Chat**, Cursor, and other tools
- ✅ Automatically **falls back** if one provider fails
- ✅ Compresses tokens to **save 15–95%** of usage

**Best of all: It's 100% free and open source (MIT License).**

---

## 📋 Prerequisites

Before you begin, make sure you have:

- ✅ A computer running **Windows 10/11**, macOS, or Linux
- ✅ A stable **internet connection**
- ✅ **VS Code** installed (free from [code.visualstudio.com](https://code.visualstudio.com))
- ✅ A **GitHub account** (to save this guide, optional)

> **Note:** OmniRoute works with **Node.js**, which we'll install in the next step.

---

## 🔧 Installation

### Step 1: Install Node.js

> **Why?** Node.js is required to run OmniRoute and its package manager `npm`.

1. Go to the official Node.js website: **[nodejs.org](https://nodejs.org)**
2. Click the **"Download Node.js (LTS)"** button
   - LTS is the stable, recommended version
3. Run the downloaded installer (`node-vXX.XX.XX-x64.msi`)
4. **IMPORTANT:** During installation, check the box that says:
   - **"Automatically install the necessary tools"** or
   - **"Add to PATH"**
5. Click **"Next"** through all screens and **"Install"**
6. **Restart your computer** (important for PATH to update)

#### ✅ Verify Installation

Open **VS Code** or **Command Prompt** and run:

```bash
node --version
# Should output: v24.20.0 or similar

npm --version
# Should output: 10.x.x or similar
