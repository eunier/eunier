## Hi there 👋

## Featured Project

### pkgstack

[`pkgstack`](https://gitlab.com/yunieralvarez/pkgstack) is a unified package manager CLI for Fedora-based Linux systems. It gives me one command surface for the package managers and setup tools I use day to day.

It manages:

- DNF packages and package groups
- Homebrew formulae, casks, and taps
- Flatpak apps
- pnpm global packages
- VS Code and VSCodium extensions
- Arch packages through an `archbox` Distrobox container
- ZVM updates
- YADM dotfile sync
- Custom TypeScript-based extras recipes

The main workflow is simple:

```sh
pkgstack sync
pkgstack search ripgrep
pkgstack restore
```

The project also includes an installer that places the CLI in `~/.pkgstack`, links it into `~/.local/bin`, and installs helper TypeScript types for custom extras recipes.

```sh
sh -c "$(curl -fsSL https://gitlab.com/yunieralvarez/pkgstack/-/raw/main/scripts/install.sh)"
```

## Links

- Featured CLI: [pkgstack](https://gitlab.com/yunieralvarez/pkgstack)

<!--
spell-checker: disable
**eunier/eunier** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
spell-checker: enable
-->
