# Little Panda Adventures — App Store Connect Metadata

Complete reference for submitting to App Store Connect. Copy-paste each field.

---

## 1. App Information

| Field | Value |
|-------|-------|
| **App Name** | `Little Panda Adventures` (23/30 chars) |
| **Subtitle** | `Interactive Stories for Kids` (28/30 chars) |
| **Bundle ID** | `com.kinexapps.LittlePandaAdventures` |
| **SKU** | `LittlePandaAdventures2026` |
| **Primary Language** | English (U.S.) |
| **Category** | Education |
| **Secondary Category** | Entertainment |
| **Content Rights** | Does not contain third-party content |

---

## 2. Keywords (100/100 characters)

```
toddler,preschool,educational,learning,bedtime,kindness,sharing,manners,children,video,storybook,fun
```

**Strategy:** Words already in the title/subtitle (`little`, `panda`, `adventures`, `interactive`, `stories`, `kids`) are automatically indexed by Apple — so they are NOT repeated in keywords to maximize the 100-character limit.

**Keyword rationale:**
- `toddler` `preschool` `children` — age-related search terms parents use
- `educational` `learning` — top parent intent keywords
- `bedtime` `storybook` — high-volume story discovery terms
- `kindness` `sharing` `manners` — matches app's core themes (unique differentiator)
- `video` — distinguishes from text-based story apps
- `fun` — high-volume modifier parents combine with other terms

---

## 3. Description (copy-paste ready)

```
Welcome to Little Panda Adventures — the interactive story app where your child makes the choices!

Join Panda on 6 heartwarming daily adventures, each teaching important life lessons through fun, animated video stories. Kids tap to make decisions that shape the story — and every choice is a gentle learning moment.

WHAT MAKES IT SPECIAL

Your child isn't just watching — they're part of the story! At key moments, two big, colorful buttons appear and your little one decides what Panda does next. Choose kindly? The story celebrates it! Choose differently? Panda has a gentle "oops" moment and learns to do better. No scolding, no punishment — just warm, encouraging lessons.

6 ADVENTURE DAYS

Day 1 — Panda's Happy Day
Morning routines: brushing teeth, getting dressed, eating breakfast, and cleaning up.

Day 2 — Panda Goes to School
First day excitement: making friends, classroom fun, drawing, and playground play.

Day 3 — Panda Learns Good Manners
Saying please, waiting your turn, and saying sorry when things go wrong.

Day 4 — Panda Learns to Share
Sharing cookies, toy blocks, and balls with friends — and why it feels good.

Day 5 — Panda Helps a Friend
Helping Bunny pick up dropped books and rescuing Duck's stuck kite.

Day 6 — Panda Learns to Say Thank You
Remembering to say thank you and sharing crayons with classmates.

DESIGNED FOR LITTLE ONES (Ages 2-6)

- Big, easy-to-tap choice buttons
- Cozy treehouse world with gentle animations
- No reading required — fully visual and narrated
- No ads with full version purchase
- Safe: no social features, no external links, no data collection

Download Little Panda Adventures and watch your child learn kindness, sharing, and good manners — one story at a time!
```

---

## 4. Promotional Text (170 chars max — can be updated without a new build)

```
Join Panda on 6 interactive video adventures! Kids make choices that teach kindness, sharing & manners. Perfect for ages 2-6. Try Days 1 & 2 free!
```

---

## 5. What's New (for version 1.0)

```
Welcome to Little Panda Adventures!

- 6 interactive story days with animated video clips
- Make choices that shape each story
- Learn kindness, sharing, manners & more
- Cozy treehouse world to explore
- Designed for ages 2-6
```

---

## 6. URLs

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://mu-haris.github.io/Little-Panda-Adventures/privacy-policy.html` |
| **Support URL** | `https://mu-haris.github.io/Little-Panda-Adventures/support.html` |
| **Marketing URL** | `https://mu-haris.github.io/Little-Panda-Adventures/` |

---

## 7. Pricing & Availability

| Field | Value |
|-------|-------|
| **Price** | Free |
| **In-App Purchases** | Yes (see section 12) |
| **Availability** | All territories |
| **Pre-order** | No (optional — enable if you want) |

---

## 8. Age Rating Questionnaire

Answer these in App Store Connect's age rating section:

| Question | Answer |
|----------|--------|
| Cartoon or Fantasy Violence | None |
| Realistic Violence | None |
| Prolonged Graphic or Sadistic Realistic Violence | None |
| Profanity or Crude Humor | None |
| Mature/Suggestive Themes | None |
| Horror/Fear Themes | None |
| Medical/Treatment Information | None |
| Alcohol, Tobacco, or Drug Use or References | None |
| Simulated Gambling | None |
| Sexual Content or Nudity | None |
| Unrestricted Web Access | No |
| Gambling and Contests | No |

**Expected Rating:** 4+ (Ages 4 and Up)

**Made for Kids:** Yes — select age band **Ages 5 and Under** (or "Ages 6-8" to cover both)

> **Important:** When you check "Made for Kids", Apple applies stricter review rules (COPPA). Your app already complies — no data collection, no behavioral ads, no external links.

---

## 9. App Privacy (Data Collection)

In App Store Connect → App Privacy:

| Question | Answer |
|----------|--------|
| **Does your app collect data?** | Yes |
| **Data types collected** | Identifiers (Advertising ID via AdMob — free version only) |
| **Is this data linked to the user's identity?** | No |
| **Is this data used to track users?** | No |
| **Purpose** | Third-Party Advertising |

> Note: If you remove ads entirely (paid-only app), select "No, we do not collect data from this app."

---

## 10. Copyright

```
2026 Kinex Apps
```

---

## 11. App Review Information

### Contact Information

| Field | Value |
|-------|-------|
| **First Name** | Muhammad |
| **Last Name** | Haris |
| **Email** | muhammadharisgift1@gmail.com |
| **Phone** | *(your phone number)* |

### Review Notes

```
Little Panda Adventures is an interactive story app for young children (ages 2-6).

HOW TO TEST:
1. Launch the app → Home screen with animated panda character
2. Tap "Play" → Day Select screen with 6 story day cards
3. Days 1 and 2 are free. Days 3-6 require in-app purchase
4. Select Day 1 → Video story plays in a wooden picture frame
5. After each video clip, two choice buttons appear — tap one to continue the story
6. At the end of a story, a completion celebration overlay appears
7. Tap the back arrow at any time to return to day selection

IN-APP PURCHASE:
- "Unlock Full Adventure" ($3.99) unlocks Days 3-6 and removes all ads
- To test locked days, tap any locked card (Day 3-6) to see the purchase overlay
- "Restore Purchases" button is available on the purchase overlay

ADS:
- Free version shows banner ads (bottom of screen) and interstitial ads (between days)
- Ads are removed after purchase
- Test ads are shown in debug builds (Google AdMob test ad units)

The app does not require login or any personal information.
```

### Demo Account

Not applicable — no login required.

---

## 12. In-App Purchase Metadata

Set this up in App Store Connect → In-App Purchases:

| Field | Value |
|-------|-------|
| **Type** | Non-Consumable |
| **Reference Name** | Unlock Full Adventure |
| **Product ID** | `com.kinexapps.LittlePandaAdventures.fullversion` |
| **Price** | $3.99 (Tier 4) |
| **Display Name** | Unlock Full Adventure |
| **Description** | Unlock all 6 story days and remove all ads forever. One-time purchase. |

### IAP Review Screenshot
Take a screenshot of the purchase overlay (the "Unlock Full Adventure" card) and upload it.

---

## 13. Screenshots Required

### iPhone 6.7" (required — iPhone 15 Pro Max / 16 Pro Max)
- **Resolution:** 1290 x 2796 px (portrait)
- **Count:** 3-10 screenshots

### iPhone 6.5" (required — iPhone 11 Pro Max / XS Max)
- **Resolution:** 1242 x 2688 px (portrait)
- **Count:** 3-10 screenshots

### iPad 12.9" (if supporting iPad)
- **Resolution:** 2048 x 2732 px (portrait)
- **Count:** 3-10 screenshots

### Recommended Screenshots (in order)

1. **Home screen** — Panda character in the meadow with "Little Panda Adventures" title
2. **Day Select** — Treehouse with 6 day cards visible (scroll to show all)
3. **Story playing** — Video clip playing inside the wooden frame with choice buttons visible
4. **Choice moment** — Close-up of two choice buttons ("Help Bunny" / "Keep Walking")
5. **Completion celebration** — Story complete overlay with confetti
6. **Purchase card** — "Unlock Full Adventure" overlay (shows value proposition)

> **Tip:** Add marketing text overlays on screenshots (e.g., "Your Child Makes the Choices!", "6 Adventures to Explore", "Learn Kindness & Sharing"). Apple allows and encourages this.

---

## 14. App Preview Video (Optional but Recommended)

| Field | Value |
|-------|-------|
| **Duration** | 15-30 seconds |
| **Format** | H.264, .mov or .mp4 |
| **Resolution** | Match screenshot resolution |

**Suggested flow:** Home screen → Tap Play → Day Select → Tap Day 1 → Video plays → Choice buttons appear → Kid taps a choice → Story continues → Celebration screen

---

## 15. Build Settings Checklist

Before uploading your build:

- [ ] Set version to `1.0` and build number to `1`
- [ ] Set deployment target to `iOS 17.0`
- [ ] Ensure `Release` build configuration (not Debug)
- [ ] Verify real AdMob IDs are in the `#else` block (not test IDs)
- [ ] App Transport Security allows HTTPS (default is fine)
- [ ] App icon is set (1024x1024 in asset catalog)
- [ ] Launch screen / storyboard is configured
- [ ] Archive via Xcode → Product → Archive
- [ ] Upload via Xcode Organizer or Transporter app

---

## 16. AdMob Verification

| Field | Value |
|-------|-------|
| **Publisher ID** | `pub-8234392075217497` |
| **app-ads.txt URL** | `https://mu-haris.github.io/Little-Panda-Adventures/app-ads.txt` |
| **Developer Website (set in AdMob)** | `https://mu-haris.github.io/Little-Panda-Adventures` |
| **Banner Ad Unit** | `ca-app-pub-8234392075217497/3909073655` |
| **Interstitial Ad Unit** | `ca-app-pub-8234392075217497/2245618132` |

### AdMob App Settings
- Set **"Designed primarily for children"** to Yes
- Set **"Ad content rating"** to G (General)
- Add your App Store URL once the app is live

---

## 17. Post-Submission Checklist

- [ ] App submitted for review
- [ ] IAP submitted for review (must be submitted WITH the binary)
- [ ] Screenshots uploaded for all required device sizes
- [ ] Privacy policy URL is live and accessible
- [ ] Support URL is live and accessible
- [ ] app-ads.txt is accessible at the URL above
- [ ] AdMob app is linked to the correct App Store listing
- [ ] Reply promptly if Apple requests additional information

---

## Quick Reference — All URLs

| Purpose | URL |
|---------|-----|
| GitHub Repo | `https://github.com/Mu-Haris/Little-Panda-Adventures` |
| Landing Page | `https://mu-haris.github.io/Little-Panda-Adventures/` |
| Privacy Policy | `https://mu-haris.github.io/Little-Panda-Adventures/privacy-policy.html` |
| Support | `https://mu-haris.github.io/Little-Panda-Adventures/support.html` |
| app-ads.txt | `https://mu-haris.github.io/Little-Panda-Adventures/app-ads.txt` |
| App Store (once live) | `https://apps.apple.com/app/little-panda-adventures/id6744206353` |
