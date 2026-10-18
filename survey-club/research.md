# Research: Survey Club - CP1C (US, CA) {iOS Only}, Facebook

## 1. Offer check
- **Offer:** Survey Club - CP1C, a free paid-survey app for iPhone. SurveyClub describes itself as connecting
  members with paid research studies (online surveys and other market-research opportunities) and rewards
  completed surveys, with cash-out by PayPal or gift cards once a minimum balance is reached.
- **Geo:** United States and Canada. **Device:** iOS only (iPhone). Set the Meta ad sets to iOS devices only;
  Android clicks won't convert.
- **Conversion:** SOI (single opt-in, a free sign-up). The pages only warm the click; the offer page does the sign-up.
- **Slug:** `survey-club`
- **Vertical:** BizOpp (paid surveys / get-paid-to). Guardrails applied: **no income or earnings claims**
  anywhere, no amounts per survey, per hour or per month, no cash imagery.
- **EPC:** $0.45 (as given). Information only.
- **Affiliate link:** `https://afflat3e3.com/trk/lnk/6BED165C-0A6B-4396-97AF-CF7A9457314A/?o=30409&c=918277&a=781113&k=EEE228FCD10CF5B2421D91E8D14DBC27&l=34952`
  (already has a `?`, so each page adds `&sub=<angle>`). The tracker domain was blocked from this build
  environment, so the final offer page couldn't be inspected. Open it on an iPhone before spending.
- **Traffic:** Facebook (Meta: Facebook + Instagram). Overrides the Facebook + Native default.
- **Test budget:** $50 split across 3 angles (~$16.67 each), one ad set per angle.

### Meta ads policy check: allowed, with restrictions
Paid-survey and get-paid-to apps are not prohibited on Meta. They sit under Meta's **unrealistic outcomes /
business opportunity and income claims** rules, which reviewers apply to the ad, the image and the landing page together:
- No earnings amounts, "make $X", "easy money", "quit your job", guaranteed outcomes, cash piles, payout
  screenshots or payment-notification images.
- **Personal attributes:** no lines that assert or imply the viewer's finances ("Need extra cash?",
  "If you're struggling with bills..."). The 2026 enforcement also catches conditional phrasing.
  Copy describes the product and second-person scenarios about time, not money trouble.
- No Special Ad Category applies (not credit, employment, housing or social issues).
- Affiliate disclosure and "results vary" line on every page (done).
- App install note: this is a web SOI link, so run it as a Traffic / Leads / Sales campaign to the bridge
  page, not an App Promotion campaign.

## 2. Avatar
1. **Who:** US and Canadian iPhone owners, mostly 22–60, lower-middle to middle income. Parents at home,
   commuters, shift workers, students, retirees. Lots of short idle moments on the phone (queues, waiting
   rooms, the bus, the couch at night) and a wish that the time counted for something. Daily frustration:
   "rewards" apps that turn out to be ad walls or game-install offers.
2. **Top 10 pain points:**
   1. Getting screened out after answering many questions (the most common survey-app complaint).
   2. Survey length estimates that are way off.
   3. Points systems where you can't tell what anything is worth (SurveyClub's own Trustpilot reviewers
      complain about long point thresholds).
   4. A cash-out minimum that feels far away.
   5. Surveys that crash, freeze or don't fit an iPhone screen (desktop-only surveys inside a mobile app).
   6. Few surveys after the first week; invitations dry up.
   7. Rewards that are slow to arrive or need ID checks.
   8. Worry about scams and about their data being sold.
   9. Juggling several survey sites to find enough to do.
   10. Feeling that their opinion is free data companies take anyway.
3. **Already tried:** big-name survey panels, points-based reward apps, "play games for rewards" apps,
   cashback apps, and giving up after a run of screen-outs.
4. **What makes them click now:** a calm, believable framing ("brands pay to hear what people think, and
   here's how it actually works"), a free iPhone app, rewards by PayPal or gift card, a quick first step,
   and honesty about screen-outs. Over-promising reads as a scam.
5. **Where they are online:** Facebook (frugal living, coupon, stay-at-home-parent and side-hustle groups),
   Instagram, Reddit (r/beermoney, r/SwagBucks, r/WorkOnline), YouTube "legit survey apps" videos, TikTok, Pinterest.

**Competitor notes:** survey and reward apps on Meta lead with "get paid for your opinion", PayPal and gift
cards, and "takes a few minutes". Reviews of survey apps (App Store, Trustpilot) center on screen-outs, wrong
length estimates, crashes on iPhone and slow rewards, so pages that set honest expectations stand out. Quiz
funnels ("which surveys fit you?") are a common low-friction pre-lander for SOI offers on Facebook.

**Market context (planning only, not used as claims on the pages):**
- Third-party reviews describe SurveyClub as legitimate with modest rewards; minimums and per-survey amounts
  differ by source and date, so none are used.
- Trustpilot shows a small number of reviews (about 29) with mixed comments; a third-party tracker claims a
  large member count. Neither is published by the offer owner for this offer, so neither is used.
- App Store figures quoted by a third-party aggregator weren't verifiable from here; not used.

## 3. Angle scores (for a cold Facebook scroller on an iPhone)
| Angle | Score | Why |
| --- | --- | --- |
| Curiosity | 5 | "Every product on the shelf was tested on people's opinions first, and most people never see those surveys" is a factual open loop; a short quiz closes it. |
| Pain Point | 4 | Anyone who has tried survey apps knows the late screen-out and the points they can't value. Naming it honestly builds trust with a skeptical audience. |
| Direct Benefit | 4 | A clear, honest end state with no money claims: free on iPhone, surveys in one app, rewards by PayPal or gift card, a few minutes at a time. |
| Social Proof | 2 | No numbers or reviews published by the offer owner for this offer; third-party figures are small or unverifiable. Guardrail: no proof → skip. |
| Fear | 1 | No real, proportionate consequence of not joining a survey app; any fear framing would be invented, and fear plus money reads as a scam on Meta. |

**Picked:** Curiosity (5), Pain Point (4), Direct Benefit (4).

**Skipped:**
- **Social Proof:** fails the guardrail (no offer-owner proof). Revisit if the network supplies the offer's own stats.
- **Fear:** no factual consequence to point to.

## 4. Formats
Paid surveys aren't in the niche table; the closest fit is a low-commitment sign-up like finance or insurance
lead gen. Facebook is cold social traffic, which converts best on a Quiz, and the Pain angle reads best as a
story. Two formats in the test: Advertorial and Quiz.

| Page | Angle | Format | Why |
| --- | --- | --- | --- |
| `pain.html` | Pain Point | Advertorial | Pain is a story (the screen-out at question 30); a short second-person article has room to set honest expectations, which this skeptical audience needs. |
| `curiosity.html` | Curiosity | Quiz | The open loop ("which surveys would you be a fit for?") fits a 4-tap quiz, the lowest-effort format for cold social. |
| `benefit.html` | Direct Benefit | Quiz | Direct is built for search intent; on Facebook the benefit lands better as a quick quiz about when they have spare minutes and how they'd like rewards. |

Quiz questions (no ZIP: the offer isn't location-based beyond US/CA):
- Curiosity: topics you know about → how often you try new products → where you live (US / Canada) → age range.
- Benefit: when you have spare minutes (picture grid) → how you'd like rewards → how much time at a sitting → age range.

## Sources
- SurveyClub on Trustpilot: https://www.trustpilot.com/review/surveyclub.com (regional mirrors: https://de.trustpilot.com/review/surveyclub.com)
- SurveyClub review (Money Pantry): https://moneypantry.com/survey-club-review/
- Paid survey app complaints, screen-outs, iPhone issues (SplitMetrics, Curious Cat listing): https://splitmetrics.com/apps/curious-cat-paid-surveys/id1234966243
- Meta Ads Policy Guide 2026, business opportunity and income claims (Enrich Labs): https://www.enrichlabs.ai/blog/meta-ads-policy-guide-2026
- Meta income claims policy (Stackmatix): https://www.stackmatix.com/blog/meta-ads-income-claims-policy
- Meta ad policy changes 2026, personal attributes (1ClickReport): https://www.1clickreport.com/blog/meta-ad-policy-changes-2026-compliance-guide
- Meta Advertising Standards: https://transparency.meta.com/policies/ad-standards/
