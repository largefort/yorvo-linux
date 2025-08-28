# Contributing to Yorvo Linux

Thank you for your interest in contributing to **Yorvo Linux**!  
Yorvo is an independent Linux distribution being built **from scratch**, and every contribution helps move the project forward.  

This guide explains how to get started as a contributor.

---

## 🔹 Ways to Contribute
- **Code**: build scripts, package manager (`ypkg`), installer tools.  
- **Packaging**: create and maintain `.ypkg` packages.  
- **Infrastructure**: repository setup, CI/CD pipelines, ISO building.  
- **Design**: wallpapers, logo, Plymouth/GRUB theming.  
- **Documentation**: write guides, explain build steps, tutorials.  
- **Testing**: run Yorvo ISOs on real or virtual hardware, report bugs.  

---

## 🔹 Getting Started
1. **Check the [Roadmap](ROADMAP.md)** to see which phase we’re in and where help is needed.  
2. **Open an Issue** if you want to discuss an idea, propose a feature, or report a bug.  
3. **Fork the repo** → make your changes → submit a **Pull Request (PR)**.  

---

## 🔹 Code Guidelines
- Use clear, commented code (Bash, Python, or C preferred).  
- For shell scripts:  
  - Always start with `#!/usr/bin/env bash`.  
  - Use `set -euo pipefail`.  
  - Ensure scripts are `shellcheck` clean.  
- For package manager (`ypkg`):  
  - Keep it minimal and modular.  
  - Document the package format and repo structure.  

---

## 🔹 Documentation Guidelines
- Place technical notes in the `docs/` folder.  
- Use Markdown (`.md`) for readability.  
- Each script should have a usage section in comments.  

---

## 🔹 Communication
- Issues and Pull Requests on GitHub are the primary way to collaborate.  
- A Matrix/Discord space will be set up for real-time discussion.  
- Please keep all discussions respectful and constructive.  

---

## 🔹 Licensing
All contributions must be compatible with the **GNU GPLv3 license**.  
By contributing, you agree to license your work under GPLv3 so that Yorvo remains free and open source.  

---

## 🚀 Final Note
Don’t worry if you’re not a seasoned developer — Yorvo is also a learning project. Beginners, testers, designers, and writers are just as valuable as coders.  

If you’re unsure where to start, check the **Issues** tab or ask in a discussion. Every small contribution helps Yorvo grow!
