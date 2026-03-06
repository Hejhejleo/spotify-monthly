# Leonard's Playlists

A personal Spotify playlist showcase website featuring monthly playlists and themed collections.

## 🎵 Features

- **Landing Page**: Overview of all playlist collections
- **Monthlies**: 12 playlists, one for each month of the year
- **New Age**: 4 chapters showing the same landscape at different times of day with an interactive accordion effect

## 🚀 Live Site

Visit: [Your GitHub Pages URL]

## 📁 Project Structure

```
.
├── index.html              # Landing page
├── monthlies.html          # Monthly playlists page
├── new-age.html           # New Age chapters page
├── css/
│   ├── shared.css         # Shared styles across all pages
│   ├── landing.css        # Landing page styles
│   ├── style.css          # Monthlies page styles
│   └── newage.css         # New Age page styles
├── img/                   # All images
├── font/                  # Custom fonts
├── js/
│   └── app.js            # Countdown timer logic
├── scripts/
│   └── generate-playlists.js  # Spotify API script
└── docs/
    └── SPOTIFY_SETUP.md   # API setup instructions

```

## 🛠️ Development

### Manual Updates
Edit the HTML files directly to add/update playlists.

### Automated Updates (Optional)
Use the Spotify API script to generate playlist HTML:

1. Follow setup in `docs/SPOTIFY_SETUP.md`
2. Run `node scripts/generate-playlists.js`
3. Copy generated HTML into your pages

## 📝 License

See LICENSE.txt
