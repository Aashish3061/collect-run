# Collect Run

**Live prototype:** https://aashish3061.github.io/collect-run/

Collect Run is a concept feature for the Razorpay Payments app, built for the Razorpay × ISB AI PM Build Challenge (Track 1). It lets a wholesale distributor who sells on credit and keeps his books in Tally see what each buyer owes, send itemised payment requests and track what gets paid, all from his phone. The owner approves every message.

## What you can try

The page shows a phone running the app, with Demo controls beside it. Start on Home and tap **Update dues**, or follow the numbered events in Demo controls:

1. Import dues from a Tally report or a photo of a paper register. AI reads it and Collect Run checks the lines against the document's own total.
2. Review today's run and approve it. A pre-send check looks for new Razorpay payments and holds any buyer who has just paid.
3. Fire payments, a part-payment and an unmatched bank transfer, and watch Collections update.
4. Skip to Friday to see follow-ups that go only to buyers who still owe.

Click **Reset demo** to start again. On a phone, tap the Demo controls button at the bottom right.

## Notes

- Concept prototype. It is not a Razorpay product and uses no Razorpay logo.
- All buyers, invoices and amounts are made up. Tally import, AI reading and matching, WhatsApp and Razorpay payment events are simulated. No live service is called and no data leaves the page.
- One self-contained HTML file. Colours, type and spacing follow tokens from Razorpay's open-source Blade design system. Inter and TASA Orbiter are embedded under the SIL Open Font License; Kalam and Noto Sans Devanagari load from Google Fonts.
