# Troubleshooting

[Back to the game](README.md) · [Controls](CONTROLS.md) · [Multiplayer](MULTIPLAYER.md)

## The game won't start

Extract the **whole** Windows ZIP before running `PuttTogether.exe`. Don't run it
from inside the archive or move the executable away from the other files. If
you're updating by hand, extract the new release into a fresh folder rather
than mixing two builds.

The current build is for 64-bit Windows. It is unsigned, so Windows or a managed
computer's security policy may block it. Check that you downloaded it from
[this repository's releases](https://github.com/RyanFDev/putt-together-releases/releases).
Don't disable security software; on a managed PC, ask its administrator about
the block. If it closes or shows an error, include that message in a bug report.

## The controls feel wrong

Open **Settings → Putting** and check stroke direction, sensitivity and handedness. The
default stroke draws back to the **right** and swings through to the **left**.
Changing handedness does not change that mouse direction.

Use **Easy** while getting used to the stroke. Hold left mouse throughout the
shot; hold right mouse as well when you want to aim without swinging. A low
distance reference in the aiming view gives more mouse travel for short putts.
Press **F1** to see your current bindings or reset eligible keys to their defaults.

## I can't connect to a friend

Make sure everyone is on the same game version and that the host has opened a
park and started hosting. On the same network, use the host's LAN address. A
VPN or virtual adapter can make the game display an address your friend can't
reach.

Across the internet, a private LAN address won't work by itself. Direct hosting
needs UDP **24747** forwarded to the host computer, with the friend using the
host's public IP. Some networks can't accept incoming connections. The optional
tunnel route is covered in the [multiplayer guide](MULTIPLAYER.md).

The host must stay in the game. There is no host migration. After a brief
disconnect, keep the client open and try **Reconnect to my ball** within two
minutes.

## An update failed

If the check or download fails, you can keep playing and try again later. Checks
have a cooldown, and GitHub may temporarily limit requests. Make sure the game
folder and its parent are writable and that the drive has room for the new build
alongside the current one.

An installation failure leaves logs and recovery instructions in a
`PuttTogether-update-*` folder under `%TEMP%`. Open **RECOVERY.txt** there for
the paths and instructions for that update. The previous installation is kept
beside the game folder with a `.previous` suffix in its name.

You can always extract a complete release into a fresh writable folder. Saved
parks and settings live separately in `%APPDATA%\PuttTogether`. Keep any previous
installation until the replacement works; don't merge the two folders.

## A park is missing or changes weren't saved

Look in **Explore parks → Your parks** and **Recovery**. Recovering a park
opens an unsaved copy: use **Save** to keep it. Recovery stores the course, not a
running round or players' positions. Named saves are in
`%APPDATA%\PuttTogether\parks`; back up the whole `PuttTogether` folder before
moving to another computer.

## Reporting a bug

[Open an issue](https://github.com/RyanFDev/putt-together-releases/issues/new),
or pass the details to the person who sent you the game. Include:

- The version on the main menu and your Windows version.
- What you did, what you expected and what happened instead.
- Whether it happens every time, and the park or hole involved.
- For multiplayer, whether you were the host or a guest and which connection
  method you used.
- A screenshot, short recording, relevant error text or saved park if useful.

Don't post passwords, tunnel tokens, private connection addresses or unrelated
files. If you're sharing a log, check it for personal paths first.
