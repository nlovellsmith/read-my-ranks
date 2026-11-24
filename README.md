# Read My Ranks

A party game you play from one link on everyone's phone.

1. Someone starts a game and shares the link or QR code.
2. Everyone adds 5 things.
3. Turns rotate: the ranker reads 5 things aloud and ranks them; everyone else guesses the ranker's order.
4. Scoring: 1 point per item in exactly the right spot, plus 1 point per pair of items in the same order as the ranker (Kendall's tau).

Single static `index.html`. Live sync runs through a free public MQTT broker (`wss://broker.emqx.io:8084/mqtt`; override with `?broker=`). The phone that starts the game hosts the state.
