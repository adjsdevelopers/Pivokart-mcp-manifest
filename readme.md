<p align="center">
  <img src="https://via.placeholder.com/120x120.png?text=P" alt="Pivokart Logo" width="120" />
</p>

<h1 align="center">🍔 Pivokart MCP Server</h1>

<p align="center">
  AI-powered Online Food Delivery Platform using MCP (Model Context Protocol)
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/pivokart-mcp?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/YOUR_USERNAME/pivokart-mcp?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/pivokart-mcp?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/YOUR_USERNAME/pivokart-mcp?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCP-Enabled-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/API-REST-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Auth-OAuth2-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://via.placeholder.com/1000x300.png?text=Pivokart+Food+Delivery+MCP" alt="Banner" />
</p>

---

# 🚀 Overview

**Pivokart MCP Server** is an AI-powered **Online Food Delivery Platform** built using MCP (Model Context Protocol). It enables AI clients like Claude, Cursor, and VS Code to interact with food delivery services in real time.

With Pivokart, you can:
- 🍽️ Discover restaurants  
- 📖 Browse menus  
- 🛒 Manage carts  
- 🚚 Place food orders  
- 🤖 Automate food ordering workflows  

---

# ⚡ Key Features

## 🍽️ Restaurant Discovery
- Search restaurants by cuisine, dish, or name  
- Filter by ratings, delivery time, and pricing  
- Discover trending and nearby restaurants  

---

## 📖 Menu Browsing
- View full menus with pricing  
- Explore dishes with details  
- Real-time availability  

---

## 🛒 Cart Management
- Add / remove items  
- Customize orders  
- View detailed bill breakdown  

---

## 🚚 Food Ordering
- Seamless checkout  
- Instant confirmation  
- Supports **Cash on Delivery (COD)** *(initial phase)*  

---

## 🤖 AI Workflows
- Smart meal recommendations  
- Budget-based ordering  
- Group / bulk ordering  
- Quick reorders  

---

# 🔐 Authentication (OAuth 2.0 + PKCE)

Secure authentication using OAuth 2.0.

## Flow

1. Redirect user to authorization URL  
2. User logs in and grants access  
3. Receive authorization code  
4. Exchange code for access token

## Example


---

# 🛠️ Setup Instructions

## ✅ MCP Configuration

```json
{
  "mcpServers": {
    "pivokart": {
      "type": "http",
      "url": "https://mcp.pivokart.in/sse"
    }
  }
}








