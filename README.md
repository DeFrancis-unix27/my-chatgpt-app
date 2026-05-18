# My ChatGPT App

A starter ChatGPT app built with the OpenAI Apps SDK. This project contains an MCP server that exposes tools to ChatGPT and can be customized with app-specific workflows, tool handlers, and UI components.

## Overview

This repo is a starting point for building a ChatGPT app. The MCP server defines the tools ChatGPT can call, while the app code can provide user-facing UI and structured responses.

Use this project to:

- Build custom ChatGPT tools
- Expose MCP server actions to ChatGPT
- Add app-specific workflows
- Prepare a ChatGPT app submission package

## Tech Stack

- OpenAI Apps SDK
- Model Context Protocol, MCP
- Node.js
- TypeScript

## Getting Started

Install dependencies:
Build the project:

pnpm run build
Run the development server:

pnpm run dev
Project Structure
.
├── src/
│   ├── server.ts
│   └── ...
├── package.json
├── README.md
└── chatgpt-app-submission.json
Customization
Before submitting this app, update the project to match your actual product:

Rename the app
Update the tool names and descriptions
Implement real tool behavior
Review tool annotations such as readOnlyHint, openWorldHint, and destructiveHint
Add or update UI components
Update this README with your app’s actual purpose
Submission
To prepare for ChatGPT app submission, generate a chatgpt-app-submission.json file after the MCP server tools and metadata are finalized.

The submission file should describe:

App name, subtitle, description, and category
Exposed MCP tools
Tool annotation justifications
Positive test cases
Negative test cases
Any review considerations
License
MIT


Before you use this as-is, change `My ChatGPT App` to your real app name.
```bash
pnpm install
