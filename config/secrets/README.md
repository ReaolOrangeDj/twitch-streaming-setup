# Secrets Directory

This directory contains API keys, tokens, and other sensitive information.
**NEVER commit actual secrets to this repository.**

## Files to Add Here:
- `twitch_token.txt` - Your Twitch API token (for chat bots, etc.)
- `streamlabs_token.txt` - Streamlabs/StreamElements API token
- `twitter_api.txt` - Twitter API credentials for auto-tweeting
- `discord_bot_token.txt` - Discord bot token for server integration
- `youtube_api.txt` - YouTube API key (for cross-platform content)
- `spotify_credentials.txt` - Spotify API for music integration

## Format:
Each file should contain just the token/key value, or simple KEY=VALUE format.

## Security:
- This directory is excluded from git via .gitignore
- Consider using a password manager or encrypted storage for production
- Rotate tokens regularly
