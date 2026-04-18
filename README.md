# Beatport Music Plex Agent
**Created by Lucy May & G. Antidote**

This is a custom Plex Metadata Agent designed to fetch high-quality metadata for electronic music directly from **Beatport**.
A plug-and-play Plex Metadata Agent that natively scrapes high-res artwork, granular EDM sub-genres, and release data directly
from Beatport without requiring API keys.

## Features
- Fetches accurate Artist Biographies and Profile Photos.
- Extensively extracts Release/Album data including high-resolution Box Art, Release Dates, Record Labels, and specific Electronic Sub-Genres (e.g., *Melodic House & Techno*, *Trance*, *Drum & Bass*).
- **Zero Configuration Required**: Uses a proprietary scraping engine to seamlessly read data directly from Beatport's Next.js framework state—completely bypassing the need for you to set up, configure, or maintain a Developer API token!

## Installation Guide

### 1. Locate your Plex `Plug-ins` Folder
* **Windows:** `%LOCALAPPDATA%\Plex Media Server\Plug-ins`
* **macOS:** `~/Library/Application Support/Plex Media Server/Plug-ins`
* **Linux:** `/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins`

### 2. Copy the Plugin
Extract the downloaded zip file. Move the `Beatport.bundle` folder into your `Plug-ins` directory.

### 3. Restart Plex Media Server
To ensure Plex loads the new framework, restart your Plex Media Server application.

## How to Use
1. Open your Plex Web Client.
2. Navigate to your Music library.
3. Click the `...` (options) menu on an artist or album and select **Fix Match**.
4. Click **Search Options**.
5. Click the **Agent** dropdown and select **Beatport**.
6. Select your match and enjoy beautiful EDM metadata! 
