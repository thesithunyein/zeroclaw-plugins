# Before you hit record — 1st-place checklist

Do these in order. Daemon should already be running with Pay QR WASM.

## 0) Merchant address (critical)

Config still has demo recipient `DYw8jCTfwHNRJhhmFcbXvVDTqWMEVFBX6ZKUmG5CNSKK`.

If you will **pay real USDC** in the video, set **your** Phantom address first:

```bash
# WSL — edit both entries (charge + watch)
nano ~/.zeroclaw/config.toml
# recipient = "<YOUR_PUBKEY>"
# then restart daemon
```

Or paste your pubkey in chat and we’ll wire it.

## 1) Warm the chat (30s, no recording yet)

Send:
```
Cobra mesa 9: R$ 25
```

Confirm reply has:
- `https://api.qrserver.com/v1/create-qr-code/...` (opens a **QR image**)
- `solana:...`

Tap the QR link once offline — must **not** be blank Phantom.

## 2) Record (~2 min)

Follow [RECORDING.md](RECORDING.md). Strongest cut: charge → QR open → Phantom scan → tiny pay → `A mesa 9 já pagou?`

If you won’t pay: still open the QR image on camera; say customer would sign; ask watch (may say not paid yet). Weaker but acceptable.

## 3) Ship the showcase (same hour)

1. Upload YouTube (unlisted)
2. Edit Earn — links in [EARN_DISCORD.md](EARN_DISCORD.md) (**fork**, not closed PR #83)
3. Post Discord `#solana-bounty` from that file
4. Optional X reply with new video URL

## 4) Done when

Judges can: watch video → open SHOWCASE.md → follow operator README → see same Telegram loop.
