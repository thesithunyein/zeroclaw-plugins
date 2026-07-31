# Record script — max-score showcase (~2:00)

Win+G / phone screen. Speak calm, continuous. Shop story, not “plugin contest.”

## Props
- Telegram Desktop or phone (Caixa bot)
- Phantom on phone
- Tiny USDC in Phantom for the close (~0.01–0.05 USDC) **or** skip pay and only show QR open (weaker)

## Timeline

| Time | Screen | Line |
|------|--------|------|
| 0:00–0:15 | Telegram chat open | “This is Caixa — my shop’s ZeroClaw agent on Telegram. I charge in reais, customers pay USDC on Solana. The agent never holds a key.” |
| 0:15–0:35 | Send `Cobra mesa 9: R$ 25` → wait for reply | “Owner message. The agent calls caixa charge and comes back with a Pay QR and a solana pay URL.” |
| 0:35–0:55 | Tap Pay QR link → QR image opens (not blank) | “Customer opens the QR and scans it in Phantom.” |
| 0:55–1:25 | Phantom pay sheet / approve small amount **or** cut back if you can’t pay | “Customer signs in their wallet. Agent never signs.” |
| 1:25–1:45 | Telegram: `mesa 9 paga?` or `watch mesa-9` → paid / monitoring | “Watch closes the loop when the invoice lands.” |
| 1:45–2:00 | Brief cut to SHOWCASE.md / operator README on GitHub | “Evening setup is in the repo. T1 custody. That’s Caixa.” |

## Messages to copy

Charge:
```
Cobra mesa 9: R$ 25
```

After pay (or to demo watch):
```
A mesa 9 já pagou?
```

Tiny pay-close (optional second invoice if R$25 is too much to settle):
```
Cobra teste: 0.02 USDC invoice_id=demo-close
```
(If the model needs clarity: “Use caixa_charge with amount_usdc 0.02 and invoice_id demo-close”)

## Must show
1. Real Telegram agent  
2. Pay QR opens an image (not Phantom download/blank)  
3. Say T1 / no keys once  
4. Watch or “paid” beat if you settle  

## Do not
- Click old Phantom `ul/browse` links from older messages — start a **new** charge after daemon restart  
- Show registry PR — show fork + SHOWCASE.md  
