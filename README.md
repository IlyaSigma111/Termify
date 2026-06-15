# Termify

Terminal-style browser for Android. Built with .NET 8 + Android WebView.

## Features
- WebView-based browsing with tab support
- Console overlay (Alt+F / tap `>_`) with commands
- 7 themes (Nord, Dracula, Catppuccin Mocha/Latte, Gruvbox, One Dark, Tokyo Night)
- Settings panel (font size, search engine, theme picker)

## Build

```bash
dotnet workload restore
dotnet build -c Release
```

APK → `bin/Release/net8.0-android/com.companyname.Termify-Signed.apk`

## Commands

| Command | Description |
|---------|-------------|
| `help` | List commands |
| `search <query>` | Search via default engine |
| `settings` | Open settings |
| `theme <name>` | Switch theme |
| `exit` | Close app |
