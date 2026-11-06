# Christmas fair stall calculator: 24 stall ideas, prices, profit and float

A free calculator for PTA, PTFA, church and club volunteers planning a Christmas fair. Tick the stalls you're running, enter how many visitors you expect, and it works out takings, costs, profit and the cash float you need to get from the bank, stall by stall and in total. It shows your top 3 earners and prints a one-page committee plan (or saves it as a PDF) with your fair's name on it.

**Use it now, no install:** [tchworks.co.uk/free/christmas-fair-stall-calculator](https://www.tchworks.co.uk/free/christmas-fair-stall-calculator/?utm_source=github&utm_campaign=fair-repo)

## Printables

**Free stall planner (A4 PDF):** [download the Release](https://github.com/wilsonryan-hue/christmas-fair-stall-calculator/releases/tag/v1.0.0-free-printable) — all 24 stalls with starting prices, blank planner, worked EXAMPLE for 300 visitors (10 default stalls → £990 takings / ~£128 costs / ~£863 profit / £160 float), tips, and a float & cash count sheet.

For the full 20-page committee pack (8-week countdown, parent + prize letters, stall/price signs, volunteer rota, raffle/tombola rules, allergen bake labels, grotto tickets, cash count): [Christmas Fair Organiser Kit](https://www.tchworks.co.uk/shop/christmas-fair-organiser-kit/?utm_source=github&utm_campaign=fair-repo) (£3.49, print at home) · [Gumroad](https://tchworks.gumroad.com/l/oyijlf?utm_source=github&utm_campaign=fair-repo).

## What's in this repo

- `index.html`: the whole calculator in one file. Open it in a browser; there's no build step and nothing to install.
- `stalls.json`: all 24 stalls with a starting price, cost per go, goes per 100 visitors, float and a tip. MIT licensed, so you can reuse it in your own sheet, app or printable.
- The full table is also below, so you can just read it.

## How the maths works

- Goes for a stall = visitors × (goes per 100 visitors ÷ 100), rounded.
- Takings = goes × price. Costs = goes × cost per go. Profit = takings − costs.
- Float = the sum of the floats for the stalls you've ticked.
- With the 10 default stalls and 300 visitors, that comes to £990 takings, about £128 costs, about £863 profit and a £160 float.

The numbers are **our own starting guesses** for a typical small UK school or community fair, not data from any real fair. Change every one to match your event; the totals update as you type.

## All 24 stalls (starting numbers)

| Stall | Price | Cost per go | Goes per 100 visitors | Float | Tip |
|---|---|---|---|---|---|
| Tombola | £1.00 | £0.00 | 35 | £20 | Donated bottles and prizes; ticket ending 0 or 5 wins |
| Raffle (on the day) | £1.00 | £0.00 | 40 | £10 | Strip of 5 tickets is popular at £2 |
| Bake sale (per cake/slice) | £0.75 | £0.00 | 60 | £20 | Donated bakes; label allergens |
| Santa's grotto | £3.00 | £1.00 | 20 | £20 | Cost is a small gift per child |
| Hot chocolate | £1.50 | £0.40 | 30 | £20 | Sachets, cups, squirty cream |
| Tea, coffee and squash | £1.00 | £0.20 | 30 | £15 | Urn, cups, milk |
| Mulled drinks (non-alcoholic) | £2.00 | £0.50 | 15 | £15 | Spiced apple or grape |
| Hook a duck | £1.00 | £0.30 | 25 | £15 | Small prize each go |
| Guess the reindeer's name | £0.50 | £0.00 | 30 | £10 | One winner, one prize |
| Sweets in the jar | £0.50 | £0.00 | 30 | £10 | Donated jar of sweets |
| Name the teddy | £0.50 | £0.00 | 25 | £10 | Donated teddy |
| Hoopla | £1.00 | £0.20 | 20 | £15 | Pocket-money prizes |
| Splat the rat | £0.50 | £0.00 | 20 | £10 | Drainpipe and a sock rat |
| Bottle stall | £1.00 | £0.00 | 25 | £15 | Donated bottles, every ticket wins |
| Chocolate tombola | £1.00 | £0.00 | 25 | £15 | Donated chocolate, every ticket wins |
| Nearly new toys and books | £0.50 | £0.00 | 40 | £20 | Donated; lots of 50p |
| Face painting | £2.00 | £0.20 | 15 | £15 | Volunteer painter, wipes |
| Glitter tattoos | £1.50 | £0.30 | 12 | £15 | Stencils and glitter |
| Christmas craft table | £2.00 | £0.60 | 15 | £15 | Make a decoration |
| Christmas cards and wrap | £1.00 | £0.40 | 10 | £10 | Bought in bulk |
| Wreaths and greenery | £8.00 | £3.00 | 3 | £20 | Pre-ordered helps |
| Sweet cones | £1.50 | £0.60 | 20 | £15 | Bagged pick and mix |
| Hot dogs | £2.50 | £0.90 | 15 | £20 | Check food safety rules |
| Secret present room | £2.00 | £1.20 | 15 | £15 | Kids buy a wrapped gift for family |

## Quick tips

- Stalls with donated stock (tombola, raffle, bottle stall, bake sale, nearly new toys) make the most, because almost every penny is profit.
- A grotto takes a lot per child, but each gift costs money, so look at the profit column, not just takings.
- A raffle or tombola sold and drawn on the day is usually an "incidental lottery" in Great Britain and doesn't need a licence, within the Gambling Commission's limits. Check the [Gambling Commission's guidance](https://www.gamblingcommission.gov.uk/) for your event.
- Card readers on the busiest stalls usually lift takings; allow for the fee per payment in your prices.

## Running the whole fair?

The [Christmas Fair Organiser Kit](https://www.tchworks.co.uk/shop/christmas-fair-organiser-kit/?utm_source=github&utm_campaign=fair-repo) (£3.49, printable) has the rest of the paperwork: an 8-week countdown, a fill-in parent letter and prize request letter, stall and price signs, a volunteer rota, raffle and tombola rules in plain English, allergen bake sale labels and a float and cash count sheet.

## Privacy

Nothing is sent or saved. All the sums happen in your browser.

## Licence

MIT. Made by [TCH Works](https://www.tchworks.co.uk/?utm_source=github&utm_campaign=fair-repo). Written with AI assistance and checked by the TCH Works team.
