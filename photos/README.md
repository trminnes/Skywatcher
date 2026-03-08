# 📷 Local Theme Photos

Place your own photos here to use them as weather backgrounds instead of Unsplash URLs.
The app will automatically detect `photos/theme/condition.jpg` paths as local files.

## Folder Structure

```
photos/
├── golf/
│   ├── sunny.jpg
│   ├── partly.jpg
│   ├── overcast.jpg
│   ├── light-rain.jpg
│   ├── heavy-rain.jpg
│   ├── storm.jpg
│   ├── snow.jpg
│   ├── fog.jpg
│   ├── night.jpg
│   └── night-rain.jpg
├── beach/        ← same 10 filenames
├── mountain/     ← same 10 filenames
├── farm/         ← same 10 filenames
├── city/         ← same 10 filenames
└── forest/       ← same 10 filenames
```

## Supported Formats
`.jpg` `.jpeg` `.png` `.webp`

## How to Use in the App
1. Open **⚙️ Setup → any theme tab** (Golf, Beach, etc.)
2. Each condition row has a **URL / Local** toggle
3. Switch to **Local** — the path auto-fills as `photos/golf/sunny.jpg`
4. Upload your photo to the matching folder in this repo
5. The app will load it directly from GitHub Pages

## Recommended Specs
| Setting | Value |
|---------|-------|
| Resolution | 1600×1000px or larger |
| File size | Under 500KB for fast load |
| Format | `.jpg` (best compression) |

## Compression Tool
Use [Squoosh](https://squoosh.app) — free, browser-based, no install needed.
Drag your photo in, set quality to ~80%, download as `.jpg`.

## Mixing Local and Remote
You can use local photos for some conditions and Unsplash URLs for others —
the app handles both simultaneously.
