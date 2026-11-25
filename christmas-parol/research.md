# Research: Playable | Merry Christmas, Light the Parol (CPL giveaway), Adsterra Native Banner, PH

## 1. Offer check
- **Offer:** Playable | "Merry Christmas, light the parol and see something special". A playable giveaway:
  the visitor taps to light a parol (the Filipino Christmas star lantern), then reaches a giveaway /
  sweepstakes registration step. Conversion type: **CPL** (pays on the lead / registration).
  The offer is not in the Zeydoo catalogue or connected offers on this account (checked Nov 25, 2026), so
  details come from the offer name the user gave: check the offer page for its allowed traffic and rules.
- **Geo:** **Philippines only.** Pages are in English, which works for PH (Taglish words like Pasko,
  Noche Buena, inaanak, tiangge used where they're natural).
- **Slug:** `christmas-parol`
- **Vertical:** Other, run as **Sweepstakes** for the legal lines (giveaway). Sweepstakes line on every page
  and in terms.html.
- **EPC / payout:** $0.25 (as given, CPL). Information only.
- **Affiliate link (BeMob campaign URL):**
  `https://fc8oa.bemobtrcks.com/go/6665c149-7980-4de3-9519-045ab5773c7c?subid=##SUB_ID_SHORT(action)##&...`
  **Same BeMob campaign ID as `new-year-click-box`.** Check in BeMob that this campaign now points at the
  parol offer (or make a new BeMob campaign for it and swap with `/swap-link`), or the two tests will mix.
  The `##...##` parts are Adsterra macros; Adsterra fills them only in the ad's own target URL. So:
  - Every CTA uses the clean BeMob URL plus the angle tag: `...6665c149-...?sub=<angle>`
  - The **Adsterra ad target URL** is the lander plus the macros (listed per angle in `ad-copy.md` and on
    the dashboard). The tracking pass-through script forwards subid, placement_id, campaign_id, banner_id,
    country_code, device_brand, browser_name, user_os, remote_country, remote_language and useragent to BeMob.
- **Traffic:** Adsterra **Native Banner** (overrides the Facebook + Native default). Mostly mobile Android,
  low-intent readers on publisher, download and streaming sites.
- **Test budget:** $50 split across 3 angles (~$16.67 each), one Adsterra campaign per angle.
- **Timing:** launched Nov 25, 2026. Simbang Gabi runs Dec 16–24; Noche Buena is Dec 24. The theme has a
  natural end date, so the test should run now; it goes stale after Christmas.

### Adsterra policy check: allowed, with restrictions
Adsterra lists sweepstakes, including giveaway sweepstakes, as a supported vertical with native and display
banners as formats. Creative rules are general: nothing misleading, no malware, no forced redirects or
unexpected downloads. What the pages and ads avoid:
- No "You won!", "Congratulations, you've been selected", fake system alerts or notification UI.
- No guaranteed prize, no specific prize or peso amount named, no odds.
- No fake countdowns or "only X left"; Christmas itself is the only timing.
- **No impersonating a government agency, politician, telecom, bank, e-wallet or store.** Fake "Christmas
  ayuda / cash gift" posts using agency and official names are a known scam pattern in PH (OVP, DSWD
  warnings), so no "ayuda", "13th month bonus" or agency wording appears as a promise anywhere.
- Every page says: a chance to win, no guaranteed prize, sponsor's official rules, a real giveaway never
  asks you to pay to collect a prize. Native line in the footer; "Advertisement · Advertorial" label.

## 2. Avatar
1. **Who:** Filipino adults 18–45 on Android phones and mobile data: students, young workers, BPO agents,
   parents, OFW families. Modest incomes; the "ber months" bring a long Christmas season (parols up from
   September) and a lot of end-of-year spending: gifts for family and inaanak, Noche Buena, trips home.
2. **Top 10 pain points:**
   1. A long gift list: parents, lolo/lola, titas, inaanak, officemates.
   2. Christmas spending all lands at once (gifts, Noche Buena, travel to the province).
   3. Fake Christmas giveaway texts and posts asking for a "processing fee".
   4. Scams using the names of government offices, telecoms, banks and e-wallets.
   5. "Giveaways" that turn into endless surveys with no end.
   6. Pages full of pop-ups and fake "you won" alerts.
   7. Not knowing whether a promo is real or who runs it.
   8. Slow pages that eat load / mobile data.
   9. Busy, tiring December (Simbang Gabi early mornings, work, shopping); wanting a small fun break.
   10. Feeling that only other people ever win raffles.
3. **Already tried:** Facebook "share to win" posts, mall and store raffles, text promos, spin-the-wheel
   apps, survey sites that never finished.
4. **What makes them click now:** the parol itself (a strong, warm symbol of Pasko), "see something
   special" curiosity, a light tap game instead of a form, free to join, and an honest page.
5. **Where they spend time online:** Facebook and Messenger, TikTok, YouTube, news and showbiz portals,
   free streaming and download sites (where Adsterra native widgets run), mobile games.

**Competitor notes:** sweepstakes on pop / native lean on "You won", fake alerts and countdowns; they burn out
and get flagged. A warm, honest pre-lander that sets the game up ("light the parol") fits the playable.

**Market context (planning only):** the parol is the iconic Filipino Christmas symbol, tied to Simbang Gabi
and the Star of Bethlehem. PH government offices (OVP, DSWD) and DTI have warned about fake Christmas cash-gift
posts and promo scams; Scam Watch Pilipinas expects spoofed bank / e-commerce "Christmas promo" texts.

## 3. Angle scores (cold, mobile native-banner reader in PH)
| Angle | Score | Why |
| --- | --- | --- |
| Curiosity | 5 | The offer's own hook ("light the parol and see something special") is an open loop the playable closes; picking a parol is almost the game already. |
| Direct Benefit | 4 | Simple end state: a free one-minute Christmas game and a chance to win. Fast, low-effort page. |
| Pain Point | 4 | The long Pasko gift list and fake Christmas prize links are real, shared frustrations; an honest story builds trust. |
| Fear | 2 | The only factual fear is prize scams; leading with scams then sending people to a giveaway reads as contradictory. Kept as a trust fact on the Pain page. |
| Social Proof | 1 | No winner numbers or reviews published by the offer owner. Guardrail: no proof → skip. Never invent winners. |

**Picked:** Curiosity (5), Direct Benefit (4), Pain Point (4).
**Skipped:** Social Proof (fails the guardrail), Fear (weak and self-defeating for a giveaway).

## 4. Formats (Advertorial + Quiz)
| Page | Angle | Format | Why |
| --- | --- | --- | --- |
| `pain.html` | Pain Point | Advertorial | Pain is a story (the gift list, the fake ayuda links); native readers expect an article, and it has room to explain how a fair giveaway works. |
| `curiosity.html` | Curiosity | Quiz | "Which parol would you light first?" as a picture grid is the open loop, flowing straight into the light-the-parol game. |
| `benefit.html` | Direct Benefit | Quiz | Direct is built for search intent; on cheap mobile native traffic the benefit lands best as 3 quick Pasko taps, then the game. |

Quiz questions (no ZIP; not location-based):
- Curiosity: which parol would you light first (picture grid) → where you'll be for Noche Buena → favorite part
  of Pasko → age range.
- Benefit: is your parol up yet → who's on your gift list → quick phone games → age range.

## Sources
- Parol (Wikipedia): https://en.wikipedia.org/wiki/Parol
- Manila Bulletin, "Pinoy parol shines brighter": https://mb.com.ph/2022/12/04/pinoy-parol-shines-brighter-symbol-of-faith-and-hope
- OVP debunks fake Christmas giveaway posts (Manila Bulletin): https://mb.com.ph/2023/12/23/ovp-debunks-fake-christmas-giveaway-posts-on-social-media
- DSWD belies P5,000 Christmas "payout" (Inquirer): https://newsinfo.inquirer.net/1874121/dswd-debunks-tiktok-post-p5000-christmas-payout-is-fake-news/amp
- DTI warns consumers on fraud sales promos: https://dti.gov.ph/archives/news-archives/dti-warns-consumers-on-fraud-sales-promos-and-text-scams
- Scam Watch Pilipinas, ber-months warning (DZRH): https://www.dzrh.com.ph/post/scam-watch-pilipinas-warns-filipinos-against-online-scams-as-ber-months-begin
- Adsterra, sweepstakes traffic: https://adsterra.com/sweepstakes
