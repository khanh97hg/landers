# Research: Surveoo (paid online surveys, Facebook)

## 1. Offer check
- **Offer:** Surveoo, a free-to-join paid survey site (US, single opt-in sign-up). Run by S GOBERT EURL
  (France). It works as an aggregator: it pulls survey opportunities from partner market-research
  panels into one member account and pays in cash value (not points) by PayPal, bank transfer or gift card.
- **Slug:** `surveoo`
- **Vertical:** BizOpp (paid surveys / "get paid to"). Treated as BizOpp for the guardrails:
  **no income or earnings claims anywhere**, no amounts per survey, per hour or per month.
- **Conversion:** single opt-in (free account sign-up). The pages only need to warm the click; the offer
  page handles the sign-up.
- **EPC:** $0.006 (as given). Recorded for information only.
- **Affiliate link:** `https://afflat3e1.com/trk/lnk/6BED165C-0A6B-4396-97AF-CF7A9457314A/?o=31078&c=918277&a=781113&k=C3A199FA6DD2ED29696AD559BDC4C30B&l=36077`
  (already has a `?`, so each page adds `&sub=<angle>`). The tracker domain didn't resolve from this
  build environment, so the final landing page couldn't be inspected; open it yourself before spending.
- **Traffic:** Facebook (Meta: Facebook + Instagram). Overrides the Facebook + Native default.
- **Test budget:** $50 split across 3 angles (~$16.67 each), one ad set per angle.

### Meta ads policy check: allowed, with restrictions
Paid survey / get-paid-to sites are not on Meta's prohibited list. They fall under Meta's
**Unrealistic outcomes / business opportunity and income claims** rules, which Meta reviews across
the ad text, image and landing page together:
- No earnings promises, amounts, "make $X", "easy money", "quit your job", lifestyle or cash imagery.
- No "guaranteed" outcomes. Surveys screen people out; the pages say so plainly.
- **Personal attributes:** ads can't assert facts about the viewer ("Need extra cash?", "Broke?").
  The copy describes scenarios and the product, not the viewer's finances.
- No Special Ad Category applies (not credit, employment, housing or social issues).
- Keep the affiliate disclosure and "results vary" line on every page (done).

## 2. Avatar
1. **Who:** US adults, mostly 25–60, lower-middle to middle income. Parents at home, shift workers,
   retirees, students, people with long commutes or waiting-room time. They're on their phone in the
   gaps of the day and like the idea of that time counting for something. Daily frustration: lots of
   idle phone time, and the apps that promise "rewards" mostly want you to watch ads or install games.
2. **Top 10 pain points:**
   1. Getting screened out of a survey after 10–20 minutes with nothing to show for it.
   2. Survey length estimates that are way off ("4 minutes" that takes 15).
   3. Points systems where you can't tell what anything is worth.
   4. High or moving cash-out thresholds; never quite reaching the minimum.
   5. Apps that are really ad walls or game-install offers.
   6. Running out of available surveys after the first few on a site.
   7. Worry about scams and sites that never pay.
   8. Spam and data-selling after signing up with an email.
   9. Juggling several survey sites to find enough surveys.
   10. Feeling their opinion is free data that companies harvest anyway.
3. **Already tried:** big-name survey apps, reward apps that pay in points, "play games for money"
   apps, cashback apps, signing up for several panels at once, and giving up after a run of screen-outs.
4. **What makes them click now:** a calm, believable framing ("brands pay for opinions, here's how
   it actually works"), a site that groups many surveys in one place, cash value instead of points,
   free with no card, and a quick, low-effort first step. Over-promising reads as a scam to them.
5. **Where they are online:** Facebook (side-hustle, frugal living, stay-at-home-parent and coupon
   groups), Instagram, Reddit (r/beermoney, r/SwagBucks, r/WorkOnline, r/sidehustle), YouTube
   "legit survey sites" videos, TikTok side-income content, Pinterest.

**Competitor and audience notes:** survey and reward apps on Meta lead with "get paid for your
opinion", "cash not points", fast PayPal cash-outs and gift cards. Trustpilot and Reddit complaints
center on late screen-outs, understated survey lengths and rejected submissions, so pages that set
honest expectations ("you won't qualify for every survey") stand out and preempt the main objection.
Quiz funnels ("which survey topics fit you?") are a common low-friction pre-lander for SOI offers on
Facebook.

**Market context (planning only, not used as claims on the pages):**
- Third-party reviews describe Surveoo as legitimate but a "second platform, not a main earner"
  (European Funding Guide UK, May 2026). Payout minimums differ by country and source (£25 UK, €20 FR).
- Trustpilot figures for Surveoo are quoted differently by different reviewers (4.0–4.3, 17k–20k
  reviews) and are not published by the offer owner, so they are not used.
- Complaint sites (SikayetVar) report "not eligible" screen-outs after many questions.

## 3. Angle scores (for a cold Facebook scroller)
| Angle | Score | Why |
| --- | --- | --- |
| Curiosity | 5 | "Companies pay to hear what ordinary people think, and most people never see those surveys" is a real, factual open loop; a quick quiz closes it. |
| Direct Benefit | 4 | Clear, honest end state with no money claims: free to join, surveys in one place, cash value instead of points, cash out by PayPal or gift card. |
| Pain Point | 4 | Anyone who has tried survey apps knows the 15-minute screen-out and the points they can't spend. Naming it builds trust; the way out is a site that pulls many surveys into one account. |
| Social Proof | 2 | No numbers or reviews published by the offer owner; third-party Trustpilot figures conflict. Guardrail: no proof → skip. |
| Fear | 1 | There's no real, proportionate consequence of not joining a survey site; any fear framing would be invented. |

**Picked:** Curiosity (5), Direct Benefit (4), Pain Point (4).

**Skipped:**
- **Social Proof:** fails the guardrail. No offer-owner numbers, and the public review figures
  disagree, so pointing to them would be shaky. Revisit if the network supplies the offer's own stats.
- **Fear:** no factual consequence to point to, and fear plus money reads as a scam on Meta.

## 4. Formats
Surveys aren't in the niche table; the closest fit is a low-commitment sign-up (like finance and
insurance lead gen). Facebook is cold social traffic, which converts best on a Quiz, and the Pain angle
reads best as a story. Two formats in the test: Advertorial and Quiz.

| Page | Angle | Format | Why |
| --- | --- | --- | --- |
| `pain.html` | Pain Point | Advertorial | Pain is a story ("the screen-out at minute 15"); a short second-person article has room to set honest expectations, which is what this skeptical audience needs. |
| `curiosity.html` | Curiosity | Quiz | The open loop ("which surveys would you be a fit for?") fits a 4-tap quiz, the lowest-effort format for cold social. |
| `benefit.html` | Direct Benefit | Quiz | Direct is built for search intent; on Facebook the benefit lands better as a quick quiz about how they'd like to use spare minutes and get paid out. |

Quiz questions (no ZIP: the offer isn't location-based):
- Curiosity: topics you know about → device you'd use → how often you shop online → age range.
- Benefit: when you have spare minutes → how you'd like to cash out → topics you know about (picture grid) → age range.

## Sources
- Surveoo review UK (European Funding Guide, May 2026): https://www.european-funding-guide.eu/uk/surveoo-review-uk
- Surveoo review (Savvy New Canadians): https://www.savvynewcanadians.com/surveoo-review/
- Surveoo complaint (SikayetVar): https://www.sikayetvar.com/en/surveoocom-us/surveoo-never-pays-me-after-i-complete-surveys
- Surveoo US SOI campaign listing (Daisycon): https://daisycon.com/fr/campagnes/17682-surveoo-us-soi/
- Surveoo URL scan (MalwareTips): https://tools.malwaretips.com/url-scan/www.surveoo.com
- Meta ads policy guide 2026, business opportunity and income claims (Enrich Labs): https://www.enrichlabs.ai/blog/meta-ads-policy-guide-2026
- Meta ad guidelines (AdsUploader, 2026): https://adsuploader.com/blog/meta-ad-guidelines
- Survey site complaints, screen-outs and length estimates (Trustpilot, Five Surveys / Branded Surveys): https://uk.trustpilot.com/review/fivesurveys.com?page=9
- Meta Advertising Standards: https://www.facebook.com/policies_center/ads
