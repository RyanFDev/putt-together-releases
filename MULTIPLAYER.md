# Play with friends

Build and play with **2–4 golfers**, including the host. Bots fill spare places for a round and leave when it ends. Everyone should use the same game version. For installation, see [Getting started](https://github.com/RyanFDev/putt-together-releases/blob/main/GETTING_STARTED.md).

## On the same network

1. The host opens a park, then chooses **Play with friends → Host this park**.
2. Choose **Copy host address** and share it with the other players.
3. Each friend opens **Play with friends**, pastes the address and chooses **Join park**. Enter the IP address alone; the game uses UDP port **24747**.
4. Joining players enter automatically. The host chooses **Back to the park**.

If Windows Firewall prompts, allow the game on your network. With several network adapters, the displayed address may belong to a VPN or virtual adapter. Use the host's address on the same local network as the joining players.

## Over the internet

Direct hosting needs a reachable connection to the host. Usually, the host forwards **UDP port 24747** on their router to their computer, then shares their public IP address. Some networks, including connections behind carrier-grade NAT, cannot accept this route. The game does not configure the router or firewall for you.

Alternatively, **Host with a tunnel** accepts WebSocket connections on **TCP port 24748**. This needs a separately configured tunnel service. Choose that hosting option, then, after setting up an ngrok account and its command-line tool on the host computer, run:

```text
ngrok http 24748
```

Keep the tunnel running and share its HTTPS address. Friends paste that address into **Join park**; the game converts it to a secure WebSocket address. This is an address for the installed game, not a browser-play link. Tunnel availability and any account limits depend on the service. See [ngrok's WebSocket setup guide](https://ngrok.com/docs/using-ngrok-with/websockets).

## Build and play a round

Everyone can build in the shared park. Press **B** for pieces, **Tab** for tool options and **F1** for controls. Save your work before replacing a park.

Open **Play a round** and have each human choose **Ready to play**. The host chooses any bots and starts the round. Editing the course clears readiness, so ready up again after changes. Take shots together, open **Scorecard** to check progress, and choose **Next hole** after holing out, or **Finish your round** on the last hole. Once everyone has finished, choose **Back to building** from the results. Your putter strikes only your ball; balls can still knock into each other. See [Controls and putting](https://github.com/RyanFDev/putt-together-releases/blob/main/CONTROLS.md).

## Disconnects and limits

The host must keep the game and session open. Closing the host ends the session; another player cannot take over. There is no public matchmaking or invitation integration.

After an unexpected disconnect, keep your game open and choose **Play with friends → Reconnect to my ball** within **two minutes**. The host keeps your ball and scores during that window, and a moving ball continues rolling. Reconnecting resets readiness.

After the window expires, choosing Leave or a fresh Join, or restarting either game, you join as a new participant. A reserved disconnected place still counts toward the four-golfer limit. Park saves and recovery copies do not restore a multiplayer session or running round.
