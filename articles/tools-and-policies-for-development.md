---
title: "Tools & Policies for Development"
emoji: "🗒️"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["memo", "wip", "nix", "環境構築"]
published: true
---

:::message
のちほど日本語にします
:::

:::message
### TODO
- 各ツール選定の理由を追加
- 必要に応じて config details なども追加
:::

https://github.com/s0r4d3v/dotfiles

## Tools

- repositories: [GitHub](https://github.com/s0r4d3v) (jj, git)
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
      - Vimium C
      - Bitwarden

## Policies

- Keep a simple, flat structure
- Install runtimes via direnv, not in Neovim
- Easy to reproduce
