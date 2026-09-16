# $KOTH

Single-file static site. No build step.

## At launch

Open `index.html`, find `CONFIG` near the top of the script, fill in:

- `ca` — the Solana mint address from pump.fun. Invalid addresses are ignored.
- `x`, `tg` — full `https://` links.

Once `ca` is set: the address and copy button appear, buy buttons link to `pump.fun/coin/<ca>`, and the live section reads DexScreener every 30 seconds. Until then everything shows a dash.

## Files

| file | made by |
|---|---|
| `index.html` | hand-written |
| `pfp.png`, `banner.png`, `og.png`, `favicon.png`, `apple-touch-icon.png` | `web_assets.py` from `koth.py` renders |
