# RC CarPlay

A CarPlay-inspired music player for FiveM. It brings a familiar in-car music experience to GTA V, with a clean interface and music playback shared between everyone inside the vehicle.

Players can add music using a link, manage the queue, control playback, and adjust the volume directly from the interface.

## Features

- Custom CarPlay-inspired interface.
- Shared music playback for everyone inside the vehicle.
- Vehicle-based music synchronization using state bags.
- Music queue system.
- Add songs using links.
- Play, pause, skip, and restart tracks.
- Volume controls and playback seeking.
- Automatically updates song information and thumbnails.
- Lightweight client-side implementation.

## Requirements

- OneSync enabled.
- [xSound](https://github.com/Xogy/xsound)

## Installation

1. Download or clone this repository.
2. Place the `rc_carplay` folder inside your server's resources directory.
3. Make sure [xSound](https://github.com/Xogy/xsound) is installed.
4. Add the following to your `server.cfg`:

```cfg
ensure xsound
ensure rc_carplay
```

5. Restart your server.

## Usage

Get inside a vehicle and use the following command:

```text
/carplay
```

The CarPlay interface will open, allowing you to add music and control playback.

## Support

Found a bug or having trouble setting things up? Feel free to open an issue on GitHub.

**[Join my Discord for more support](https://discord.gg/2fRQwbUHH3)**


