---
title: "Tools & Policies for Development"
emoji: "🗒️"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["memo", "Nix", "環境構築"]
published: true
---

> のちほど日本語にします

## Tools

- repositories: GitHub (jj, git)
- environment: Nix (Home Manager)
  - configured in Nix
    - papers: $\LaTeX$
    - slides: Marp (marp-cli)
    - editor: Neovim (Nixvim)
    - terminal: Ghostty, Starship, Tmux
  - configured in each app
    - memo: Notion
    - todo: Notion
    - passwords: Bitwarden
    - browser: Google Chrome

## Policies

- Keep simple & flat structure
- Install runtime in direnv, not in Neovim
