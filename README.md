# GoAII Timer

A fan-made timer for the board game **[Guards of Atlantis II](https://boardgamegeek.com/boardgame/267609/guards-of-atlantis-ii)**. It sits on a tablet in the middle of the table and runs the clocks, so the game keeps moving even when someone really needs to think about that minion push. If you want, every player can also join from their own phone and run their clock from their seat.

## How it works

The timer follows the structure of the game itself: rounds of four turns, an optional strategy countdown before each turn, and an optional break between rounds. The action phase works like a chess clock with one shared time bank per team. Tap your name when you start thinking, tap again when you're done. Once everyone has acted, the app moves to the next turn on its own.

A few details that came from playing it at the table:

- Supports 2v2 up to 5v5, with editable player names.
- The time bank scales with the player count. Default is 10 minutes per player, so a 3v3 gives each team 30 minutes.
- Started someone's clock by accident? Undo reverses the last 30 actions. You can also nudge either team's bank by 1 or 5 seconds, and the net correction stays visible under the clock, so nobody wonders whether the clock was touched.
- To pause, tap the strategy or break clock itself.
- Sound alerts (with a mute button), the screen stays awake during a game, and once loaded it works without internet.

## Phone remotes

Start a shared session on the tablet and everyone else joins from their phone: scan the QR code, open the shared link, or type in the 4-letter code. Each player picks their team, enters their name, and gets one big button for their own clock, along with their team's remaining bank, the other team's bank, and whose clock is running right now.

The tablet stays the boss. If a phone drops out, nothing is lost: rejoin with the same code and claim your player again. Connections are peer-to-peer (WebRTC through the free [PeerJS](https://peerjs.com) broker), so this one feature needs internet on all devices.

## After the game

End Game shows how many rounds you played and the real time on the clock, a pie chart per team of how the thinking time was split, and a table per player with total time, turns played, and average per turn. "Turns" only counts turns you actually took part in, so sitting one out doesn't wreck your average.

## Installing it like an app

Open the site in Chrome on Android, tap ⋮ and choose *Add to Home screen*. It runs full screen after that, and updates arrive by themselves a launch or two after I push them.

## Disclaimer

This is an unofficial fan project. *Guards of Atlantis II* is a game by Wolff Designa. This timer is not affiliated with or endorsed by them, and contains no game content or artwork. Go buy the game, it's excellent.
