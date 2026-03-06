# Spotify Playlist Generator

This script fetches your playlists from Spotify and generates HTML for your site.

## Setup

1. Go to https://developer.spotify.com/dashboard
2. Log in with your Spotify account
3. Click "Create app"
   - App name: "Playlist Generator" (or anything)
   - App description: "Generate HTML for my website"
   - Redirect URI: http://localhost (not used but required)
   - Check "Web API"
4. Click "Settings" and copy your:
   - Client ID
   - Client Secret (click "View client secret")

5. Get your Spotify User ID:
   - Go to your Spotify profile
   - Click "..." → Share → Copy link to profile
   - Your user ID is the part after `/user/`
   - Example: `spotify:user:1234567890` → user ID is `1234567890`

6. Edit `generate-playlists.js` and fill in:
   ```javascript
   const CLIENT_ID = 'your_client_id_here';
   const CLIENT_SECRET = 'your_client_secret_here';
   const USER_ID = 'your_user_id_here';
   ```

## Usage

Run the script:
```bash
node generate-playlists.js
```

This creates `generated-playlists.html` with your playlist HTML.
Copy the content and paste it into your `monthlies.html` file.

## Notes

- Run this script whenever you want to update your playlists
- The script uses Node.js built-in modules (no npm install needed)
- Your credentials stay local - never commit them to GitHub
