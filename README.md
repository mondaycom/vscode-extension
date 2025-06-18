# monday.com VS Code Extension

A Visual Studio Code extension that brings your monday.com workspace directly into your development environment. Manage tasks, view item details, and create feature branches without leaving your editor.

![Activity Bar](https://dapulse-res.cloudinary.com/image/upload/vscode-extension/activity-bar.png)

## Table of Contents

- [✨ Features](#features)
  - [🔑 Authentication](#-authentication)
  - [📋 Board Context](#-board-context)
  - [📝 Items Management](#-items-management)
  - [⚡ Item Actions](#-item-actions)

## Features

### 🔑 Authentication

- Set your monday.com API token to access your workspace
- Token is securely stored in VS Code's secret storage
- Secured OAuth flow with monday.com

### 📋 Board Context

- Quick access to your recent monday.com boards
- Set a context board to view and manage its items
- Search through board items easily

### 📝 Items Management

![Items list](https://dapulse-res.cloudinary.com/image/upload/vscode-extension/items-list.png)

- View all items assigned to you in the selected board
- Search and filter items by name or ID
- Detailed item view showing:
  - Item name and ID
  - Group information
  - Custom column values
  - Current status

### ⚡ Item Actions

Each item has three quick actions:

- **View Details** - Open detailed item view
  ![View Details](https://dapulse-res.cloudinary.com/image/upload/vscode-extension/item-view.png)

- **Create Branch** - Automatically create a feature branch based on the item identifier

- **Open Pull Request** - Create a pull request on GitHub based on the item's branch

- **Open in monday** - Open the item in monday.com web interface

- **Solve with AI** - Enrich IDE AI chat with the item context
