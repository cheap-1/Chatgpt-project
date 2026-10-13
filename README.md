# Chatgpt-project

## Desktop GUI

Start the server with `node server.js`, then open `http://localhost:8082/` in your XFCE browser. You can also launch the default browser from a terminal with `xdg-open http://localhost:8082/`.

The page connects to the server over WebSocket. Enter a room hash, choose a tank profile and count, then select **Spawn session**. Live status shows active and total spawned counts plus a roster of bots with their IDs, names, tank profiles, and join state.

**Show the bot’s game view** is enabled by default for a single bot. The bot’s canvas drawing is streamed to the control page’s **Bot game view** panel; this visualizes the existing bot client and does not open a separate Chromium window. Turn the option off to spawn multiple bots without streaming a view. When running remotely, use the server URL printed at startup instead of `localhost`.