# VS Code Configuration

This repository includes VS Code workspace configuration to enhance the development experience for Jekyll blog maintenance.

## Quick Start

1. Open this folder in VS Code
2. When prompted, install the recommended extensions
3. Use the tasks to run common Jekyll commands

## Recommended Extensions

The workspace recommends the following extensions for Jekyll development:

- **Ruby** (`rebornix.ruby`) - Ruby language support
- **Markdown All in One** (`yzhang.markdown-all-in-one`) - Enhanced markdown editing
- **markdownlint** (`davidanson.vscode-markdownlint`) - Markdown linting
- **Jekyll Syntax** (`ginfuru.ginfuru-vscode-jekyll-syntax`) - Jekyll syntax highlighting
- **Shopify Liquid** (`sissel.shopify-liquid`) - Liquid template language support

## Available Tasks

Press `Ctrl+Shift+B` (or `Cmd+Shift+B` on Mac) to access build tasks:

- **Serve Jekyll Site** - Start the local Jekyll development server
- **Build Jekyll Site** - Build the static site
- **Install Dependencies** - Run `bundle install` to install Ruby dependencies

## Workspace Settings

The workspace is configured with:

- **File Associations**: Markdown and HTML files are properly recognized
- **File Exclusions**: Build artifacts (`_site`, `.jekyll-cache`) are hidden from the file explorer
- **Search Exclusions**: Build artifacts are excluded from search results
- **Markdown Settings**: Word wrap is enabled for markdown files

## Using the Workspace

You can open the workspace by:

1. Opening the folder directly in VS Code
2. Opening the `20kyrsgroove.code-workspace` file

Both methods will apply the same configuration.
