---
layout: default
title: Getting Started
---

# Getting Started Guide

## Installation

### Step 1: Sign Up
1. Visit https://example.com
2. Click "Sign Up"
3. Enter your email
4. Verify email address

### Step 2: Install CLI
```bash
npm install -g example-cli
```

### Step 3: Authenticate
```bash
example login
```

## Your First Project

### 1. Create Project
```bash
example create-project my-project
```

### 2. Initialize
```bash
cd my-project
example init
```

### 3. Deploy
```bash
example deploy
```

## Monitoring Your Pipeline

### View Pipeline Status
```bash
example status my-project
```

### View Logs
```bash
example logs my-project
```

### Stop Pipeline
```bash
example stop my-project
```

## Troubleshooting

**Q: Authentication fails**
A: Run `example logout` then `example login` again.

**Q: Installation issues**
A: Check Node.js version (14+) is installed.

**Q: Need more help**
A: Visit https://example.com/support