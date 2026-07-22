# Hi there 👋

## Featured Project

### NOR (Organise Repos)

[`nor`](https://gitlab.com/yunieralvarez/nor) is a unified CLI for managing
packages, systemd units, editor extensions, dotfiles, and reproducible
workstation state. It gives me one command surface for the package managers and
setup tools I use day to day.

NOR provides its full set of integrations on Linux. It can also be used on
macOS when Homebrew is enabled in the user configuration; Homebrew is currently
the only compatible package manager on macOS.

On Linux, it manages:

- Pacman / AUR packages
- DNF packages and package groups
- Homebrew formulae, casks, and taps
- Nix profile packages
- Flatpak apps
- npm and pnpm global packages
- .NET global tools
- VS Code and VSCodium extensions
- Arch packages through an `archbox` Distrobox container
- systemd services, sockets, and timers
- ZVM updates
- YADM dotfile sync
- Custom TypeScript package recipes

The main workflow is simple:

```sh
nor sync
nor search ripgrep
nor restore
```

Package inventories are saved as portable state, making it easier to update,
rebuild, or migrate a workstation.

## Links

- Featured CLI: [nor](https://gitlab.com/yunieralvarez/nor)

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
