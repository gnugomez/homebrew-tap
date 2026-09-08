# homebrew-tap

Homebrew packages for [gnugomez](https://github.com/gnugomez)'s projects.

```sh
brew tap gnugomez/tap && brew trust gnugomez/tap
brew install majordomo
xattr -dr com.apple.quarantine /Applications/Majordomo.app
```

The `xattr` line clears Gatekeeper's quarantine (Majordomo is not
notarized); skip it if you prefer approving the app once under
System Settings → Privacy & Security instead.

The casks here are updated automatically by each project's release workflow.
