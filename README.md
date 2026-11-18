# AI Music Check

Drop in a song and it tells you how likely it is to have come out of an AI music generator like Suno or Udio. Everything runs on your own computer - nothing is uploaded. An optional vocal check lifts the voice out of the mix and scores it on its own, which catches AI vocals sung over a real band. Treat it as a guide, not a verdict: AI parts mixed into a human production can still slip through.

## Download

Get the latest build from the [Releases page](https://github.com/enteroutside/ai-music-check/releases/latest).

Windows 64-bit. No installer - it's a single executable, run it where you like.

## Verifying the download

This is a personal project and the executable isn't code-signed, so Windows SmartScreen will warn you the first time you run it. You can check the file is exactly the one published here:

- **SHA-256** (v1.1.1.0): `9d9e08f4d9e327114745f38603142281a7beb0c292fc339b8146c2c6a598ca0f`

In PowerShell:

```powershell
Get-FileHash .\ai-music-check-1.1.1.0.exe -Algorithm SHA256
```

## About

Built by [EnterOutside](https://www.enteroutside.com). Free to use, shared as-is with no support promised.
