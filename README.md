# MusicBot

A powerful and easy-to-use Discord music bot with support for YouTube, Spotify, SoundCloud, and more. Fully customizable and self-hosted.

## Features

• Multi-source playback: YouTube, Spotify (tracks, albums, playlists), SoundCloud and Apple Music links, plus search by song name
• Interactive player panel: buttons for pause, resume, skip, previous, loop, shuffle, autoplay, filters and queue
• Audio filters: bassboost, nightcore, treble, pop, loud, karaoke and more, with /clearfilters to reset
• Queue control: view, remove, move, shuffle and clear the queue, plus play history
• Loop modes: off, track or queue
• Autoplay that keeps music going after the queue ends
• 24/7 mode to keep the bot in the voice channel
• Vote skip (50% of the voice channel) and a configurable DJ role
• Lyrics through the Genius API
• Stats and uptime: /stats, /uptime and a built-in Express server with / and /stats JSON endpoints for monitoring
• Optional logs channel for bot events  

# **Commands**
**Category**	                  **Commands**
Playback	                     /play, /pause, /resume, /skip, /previous, /seek, /voteskip, /stop, /volume
Queue	                        /queue, /nowplaying, /shuffle, /loop, /remove, /move, /clearqueue, /history
Modes and filters	            /247, /autoplay, /filter, /clearfilters
Extras	                     /lyrics, /djrole (admin), /restart (admin)
Info	                        /stats, /uptime, /ping, /invite, /support, /help

## Getting Started

1. Clone the repository  
   ``git clone https://github.com/Unknownzop/MusicBot.git``

2. Navigate into the project directory  
   ``cd MusicBot``

3. Install dependencies  
   ``npm install``

4. Set up environment variables  
   ``cp .env.example .env``  
   Edit ``.env`` with your Discord bot token

5. (Optional) Customize settings in  
   ``config.js``

6. Start the bot  
   ``node index.js``

## License

This project is licensed under the GPL-3.0 License  
[View License](https://github.com/Unknownzop/MusicBot/blob/main/LICENSE)
