# homebrew-tap

Homebrew packages for [gnugomez](https://github.com/gnugomez)'s projects.

```sh
brew tap gnugomez/tap && brew trust gnugomez/tap
brew install --no-quarantine majordomo
```

`--no-quarantine` because Majordomo is not notarized; without it, macOS asks
for a one-time approval under System Settings → Privacy & Security.

The casks here are updated automatically by each project's release workflow.
