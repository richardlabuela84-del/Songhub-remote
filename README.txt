SongHub Remote — iPhone PWA prototype

This is a functional UI prototype, not an official iOS build.
Features:
- SongHub IP + port connection
- WebSocket connection attempt
- Demo mode
- Song search/list
- Queue management
- Play/pause/previous/next controls
- Lyrics screen

The exact production protocol still needs to be verified against the SongHub server.
The prototype currently sends JSON WebSocket messages such as:
{"type":"queue_add","songId":"01"}
{"type":"queue_remove","index":0}
{"type":"play_pause"}
{"type":"previous"}
{"type":"next"}

To use on iPhone, host this folder on HTTPS and open it in Safari, then Share > Add to Home Screen.
