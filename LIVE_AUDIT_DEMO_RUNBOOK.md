# 🎬 Live Audit Demonstration Runbook
## Screen-Sharing Navigation Protocol for Swastik Agnihotri
### Target Website: `https://rishikeshyogaashram.com/`
**Presentation Deck:** *From Website Audit to Digital Growth — 10 Opportunities I Found for Rishikesh Yoga Ashram*

---

## 🛠️ PRE-CALL BROWSER SETUP (Complete 15 Mins Before Interview)

Open Google Chrome with a dedicated clean window and open these **4 pre-loaded tabs**:

- **Tab 1:** Slide Deck / Presentation (`slides.html` or `NAVAVYUH_INTERVIEW_PRESENTATION.md`).
- **Tab 2:** `https://rishikeshyogaashram.com/` (Clean Desktop View, scrolled to top).
- **Tab 3:** `https://rishikeshyogaashram.com/` in an **Incognito Window** (To demo the 2-second popup cleanly).
- **Tab 4:** `https://search.google.com/test/rich-results` (Pre-tested with homepage URL showing 0 Course Schemas).

> **💡 Screen Sharing Pro-Tip:**  
> Press `Cmd +` (or `Ctrl +`) once in Chrome to zoom the page to **110%** so the founder can read text and DevTools clearly on their screen.

---

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                              THE 5 LIVE DEMONSTRATION TOUCHPOINTS                      │
├────────┬──────────────────────────────────────────┬──────────────┬─────────────────────┤
│ DEMO # │ GROWTH OPPORTUNITY                       │ BROWSER VIEW │ TARGET TIME         │
├────────┼──────────────────────────────────────────┼──────────────┼─────────────────────┤
│ 1      │ Opp 01: Homepage Overload & Mobile UI    │ Slide 5 / T2 │ 04:45 – 06:45 (2m)  │
│ 2      │ Opp 02: Cross-Domain Checkout Leak       │ Tab 2        │ 06:45 – 08:15 (90s) │
│ 3      │ Opp 03: 2-Second Premature Popup         │ Tab 3        │ 08:15 – 09:30 (75s) │
│ 4      │ Opp 05: YouTube Preload Network Bloat    │ Tab 2 + Dev  │ 10:45 – 12:00 (75s) │
│ 5      │ Opp 06: URL Typo (/Arial-yoga.php)       │ Tab 2 Nav    │ 12:00 – 13:00 (60s) │
└────────┴──────────────────────────────────────────┴──────────────┴─────────────────────┘
```

---

# 📍 DEMO 1: Homepage Overload & Side-by-Side Mobile Comparison (Opp 01 & 09)

### 1. Browser Action
1. On **Slide 5** of your presentation, point out the **Real Mobile Phone Screenshots** (`client_mobile.jpg` vs `competitor_mobile.jpg`).
2. Click on the left phone image to zoom into the real screenshot of `rishikeshyogaashram.com` showing the overlapping green WhatsApp & red "Enquire Now" pills covering the text *"teachers should come to the town to undergo..."*.
3. Click on the right phone image to zoom into the real screenshot of `vinyasayogaacademy.com` showing the real classroom photo, the 4 stat cards (*10,000+ Students Trained, 15+ Yrs, 100+ Countries, 4.8★*), and the clean fixed bottom action bar.

### 2. What to Point to on Screen
- **Left Screenshot (Client):** Floating buttons overlapping text, large logo graphic, and 6-paragraph history before courses appear.
- **Right Screenshot (Competitor):** Immediate real student photo in class, 4 trust stats, and Yoga Alliance RYS 500 stamp in the first 3 seconds.

### 3. What to Say Verbatim:
> *“Sir, let's look at real mobile screenshots of your website on the left versus the top-ranking competitor on the right.*
> 
> *On your website, you have rich authentic knowledge. But on a smartphone screen, a student from Germany or the US has to scroll through several paragraphs of text before finding your course cards, dates, or fees. Furthermore, the floating buttons cover the text.*
> 
> *The top competitor on the right establishes immediate trust in the first 3 seconds: real students in class, student count, and Yoga Alliance certification.*
> 
> *We won't delete your deep reading—we simply bring your course cards, batch dates, and trust proof to the top 3 seconds of the phone viewport, keeping detailed philosophy below.”*

---

# 📍 DEMO 2: The Cross-Domain Booking Journey (Opp 02)

### 1. Browser Action
1. Switch to **Tab 2** (`rishikeshyogaashram.com`).
2. In the header navigation, click the **"Booking"** button.
3. Point directly to the browser URL address bar showing:
   ```
   https://gurukulyogashala.com/payment.php
   ```

### 2. What to Say Verbatim:
> *“This is one of the most critical conversion opportunities on the website.*
> 
> *Imagine a student has spent 15 minutes evaluating your teacher training, decides to book, and clicks 'Booking'.*
> 
> *Suddenly, their browser redirects to a completely different website: `gurukulyogashala.com`.*
> 
> *At that exact moment of payment, the student wonders: 'Am I still on the right website? Is my money safe?'*
> 
> *That is the worst possible moment to introduce uncertainty—because this is when the visitor is closest to becoming a paying student.*
> 
> *My priority would be working with your developer to build a seamless, on-brand booking experience so the student never feels they have left the school.”*

---

# 📍 DEMO 3: The 2-Second Premature Popup (Opp 03)

### 1. Browser Action
1. Switch to **Tab 3** (Fresh Incognito Window with `https://rishikeshyogaashram.com/`).
2. Count out loud: *“One... Two...”* ➔ Watch the full-screen Enquiry Form cover the viewport.

### 2. What to Say Verbatim:
> *“Look at this: within two seconds of arriving, before a student has even read the first course description, a large form blocks the screen asking for personal details.*
> 
> *The issue isn't having an enquiry form—it's **timing**.*
> 
> *First, let the student understand the school. Build trust. Then offer contact options when they are actually ready.*
> 
> *Aligning contact prompts with natural user intent improves conversion rates and creates a smoother mobile experience.”*

---

# 📍 DEMO 4: YouTube Loading Before Visitor Asks for It (Opp 05)

### 1. Browser Action
1. In **Tab 2**, open Chrome DevTools (`F12` or `Cmd + Option + I`).
2. Click on the **Network** tab.
3. Hard-reload the page (`Cmd + Shift + R`).
4. Type `youtube` in the Network filter box.

### 2. What to Point to on Screen
- Point to the waterfall of network requests initiated by YouTube embeds while the user is still at the top of the page.
- Point to the transfer size of third-party assets downloaded before any video is played.

### 3. What to Say Verbatim:
> *“Even though the student review videos are far down the page and I haven't clicked Play, the browser is already downloading hundreds of kilobytes of YouTube player code.*
> 
> *It's like turning on the television in a hotel room before the guest even decides if they want to watch TV.*
> 
> *Instead, we can show a lightweight preview thumbnail. The actual video player loads smoothly on demand when the student clicks Play.*
> 
> *This significantly speeds up initial mobile page loads without removing a single video review.”*

---

# 📍 DEMO 5: Structural Typo in Course URL (Opp 06)

### 1. Browser Action
1. In the main navigation bar, hover over **"Short Courses"** dropdown.
2. Right-click on **"Aerial Yoga Teacher Training"** ➔ Click **Inspect Element**.
3. Point to the `href` attribute:
   ```html
   <a href="./Arial-yoga.php">Aerial Yoga Teacher Training</a>
   ```

### 2. What to Say Verbatim:
> *“Notice the URL slug for Aerial Yoga: it is spelled as `/Arial-yoga.php`—like the computer font 'Arial', rather than the yoga practice 'Aerial'.*
> 
> *One small typo is not going to break a website. But URLs are part of the site structure and how search engines connect search queries to pages.*
> 
> *Having clean, correct URLs ensures search engines understand the page with 100% precision and reinforces professional quality.”*

---

## 🚨 EMERGENCY / FAIL-SAFE PROTOCOLS

| Scenario | Immediate Action to Take |
|---|---|
| **Website is Down / Slow During Call** | Say: *“I have offline snapshots and screenshots saved from my audit. Let me pull up the exact capture.”* (Use slide screenshot modal). |
| **Founder Asks “How would you fix it?”** | Give the high-level strategic direction (e.g. *“I'd first make the checkout consistent and on-brand with your developer before deciding the exact technical route”*). **Do not dump free code!** |
| **Founder Asks “Did you use automated tools?”** | Say: *“I ran initial automated scans, but every single issue I'm showing you today was manually inspected, verified in live DevTools, and connected to student psychology by me.”* |
