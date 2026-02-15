# Edith-Doris_IP

GitHub repo link: https://github.com/hxttm/Edith-Doris_IP.git


# Dream
Dream is a web-based study companion built around one simple idea: **students stay consistent when studying feels rewarding, social, and visually motivating. Our tagline, “Dream With Purpose.”, reflects how Dream turns everyday study sessions into meaningful progress—where time spent focusing directly nurtures your 3D study buddy, earns gems, and unlocks access to community-created notes.
Dream is tailored for Singapore students (PSLE / Secondary / Poly / JC) who juggle heavy content like Stats, Operations, and exam modules. Instead of “study harder,” Dream focuses on “study smarter and consistently”—using a timer-driven reward loop, quests, and peer motivation through chat and leaderboards.

 
## Design Process
 
### Who this website is for
**Primary users:** Singapore students who need structure, motivation, and fast access to revision materials.  
**Secondary users:** Students who create notes and want passive “earnings” from uploading and selling them.

### What users want to achieve
- **Stay focused** (reduce distractions while studying -- focus mode do not allow switching of tabs)
- **See progress clearly** (weekly progress + calendar study history)
- **Feel motivated daily** (quests + daily spin rewards)
- **Learn faster** (notes marketplace + owned notes in PDF form + access notes while in focus mode)
- **Feel supported** (group chats / DMs + leaderboard competition)

### Why Dream is the best way to help them
Dream combines a **study timer app loop (like Study Bunny)** with a **gem economy** and a **3D pet nurturing system**:
- Study sessions → earn gems → complete quests → keep buddy healthy
- Gems → buy notes in the marketplace
- Social systems (chat + leaderboard) → encourage consistency and peer support

### Key UX decision: Mascot selection = full theme identity
During account creation, users pick a study buddy which **sets the site-wide UI theme**:
- **Blue theme** = Blue study buddy + matching 3D model + blue UI styling
- **Orange theme** = Orange study buddy + matching 3D model + orange UI styling  
This makes the app feel “owned” and personal—students immediately feel attached to their buddy and interface.

### User Stories

#### Onboarding & Identity
- As a **new user**, I want to **sign up with email + password**, so that I can access Dream.
- As a **new user**, I want to **choose a study buddy**, so that my whole UI theme matches my mascot (blue/orange).
- As a **returning user**, I want to **log in quickly**, so that I can continue where I left off.

#### Focus & Productivity
- As a **student**, I want to **start a focus timer**, so that I can study with structure.
- As a **student**, I want **focus mode to prevent page switching**, so that I don’t get distracted.
- As a **student**, I want to **access notes while the timer runs**, so that my studying is smoother.
- As a **student**, I want **study sounds (white noise / lofi / rain / brown noise / cafe ambience)**, so that I can stay calm and focused.

#### Progress Tracking
- As a **student**, I want to view **weekly progress**, so that I can see consistency and track my progress.
- As a **student**, I want a **calendar of study history (daily/monthly)**, so that I can track long-term habits.

#### Motivation & Rewards
- As a **student**, I want **daily quests**, so that I know exactly what to do each day.
- As a **student**, I want to **fill my buddy’s health bar**, so that my buddy stays “alive” and healthy.
- As a **student**, I want a **daily spin wheel**, so that I can get surprise rewards or challenges.

#### Notes Marketplace
- As a **buyer**, I want to **browse notes**, so that I can revise faster.
- As a **buyer**, I want to **preview notes with reviews/ratings**, so that I can decide if it’s worth my gems.
- As a **buyer**, I want to **access purchased notes as PDFs**, so that I can study anytime.
- As an **uploader**, I want to **upload notes with a description and price**, so that I can earn gems passively.

#### Social & Competition
- As a **student**, I want to **chat in group chats and DMs**, so that studying feels less lonely.
- As a **competitive student**, I want a **country ranking leaderboard (Top 50)**, so that I can compare study hours with others.

#### Safety & Support
- As a **parent/student**, I want **privacy + parental controls**, so that the app feels safe.
- As a **user**, I want a **Contact Us** page, so that I can get help.

### Wireframes / Mockups / Diagrams
- Figma wireframes: [https://www.figma.com/design/ASkwLG3INBLK7ddpk4I0pB/IP_HighFid_edith?node-id=0-1&t=aczgleC13wHR1F8M-1]
- Figma Wireframe files are stored in: C:\Users\doris\OneDrive\Desktop\IP\id2\Edith-Doris_IP\wireframe\IP_wireframes.fig 

## Features

### Existing Features

**1. Splash / Branding**
- Presents the tagline **“Dream With Purpose.”** and introduces the mascot-based identity.

**2. Login**
- Email + password login for returning users.

**3. Create Account (Mascot Selection = Theme)**
- Choose a mascot (blue/orange), then email + password.
- Theme affects visuals across the website, including the buddy page’s 3D model.

**4. Dashboard**
- Weekly progress overview
- Quick access to:
  - Focus mode timer
  - Active quests
  - Study buddy preview
  - Notes marketplace
  - Leaderboard
  - Daily spin

**5. Focus Mode**
- Timer-based study session
- Restricts leaving the focus experience (anti-distraction intent)
- Allows access to notes while studying
- Sound design: selectable study ambience from 5 sound options

**6. Study Buddy**
- 360° 3D viewer of the chosen buddy
- Health bar linked to quest completion
- Shows “Fill Health Bar” quests and earning rates

**7. Daily Spin Wheel**
- Daily chance to receive either a reward or a challenge (e.g., focus session task or gems)

**8. Calendar**
- Displays study history by day and month to reinforce streak behavior

**9. Notes Marketplace**
- Browse notes listings
- Preview page includes description + reviews + star ratings
- Purchase notes using gems

**10. Upload Notes**
- Uploaders add description + set prices (supports passive earning concept)

**11. Your Notes (PDF Library)**
- Stores purchased notes and displays them in PDF form

**12. Leaderboard (Country)**
- Shows **Singapore Top 50** ranking by study hours
- Diamonds/gems do **not** affect ranking (hours only)

**13. Chat**
- Supports group chats and DMs to encourage peer motivation and belonging

**14. Settings**
- Account adjustments
- Privacy settings + parental controls

**15. Contact Us**
- Support access for users


In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Study together! -- students can "study together" in chats, whereby you can set break times and chat in between study sessions. Studying together will encourage students to work hard and thrive with their friends and feel less lonely while studying
- 

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)  
  - Used for structuring pages and UI layout.

- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)  
  - Used for responsive layouts, theming (blue/orange), and UI styling.

- [JavaScript (Vanilla)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
  - Used for interactivity such as theme switching, timers, UI updates, and page logic.

- [Sketchfab Embed (WebGL 3D Viewer)](https://sketchfab.com/developers/viewer)  
  - Used to embed 360° 3D study buddy models in an iframe.

- [Google Sheets GViz Query Endpoint](https://developers.google.com/chart/interactive/docs/querylanguage)  
  - Used as a lightweight API-like data source for leaderboard display (reads from a Google Sheet using a query).

- [Adobe XD](https://www.adobe.com/products/xd.html)  
  - Used for wireframes and UI planning.


## Assistive AI

In this section you should document the process of using AI tools eg, ChatGPT, Gemini etc to help you with the development of features/functionalities of your web application. (Failure to document your use of AI tools will result in loss of marks.) Example below:

1) **Leaderboard “API” integration (Google Sheets GViz)**
- AI assisted with forming the GViz query URL, parsing the JSON response format, and safely rendering rows.
[https://www.perplexity.ai/search/ways-to-create-an-api-database-onHk53fuSjCmH_5A4xcqeg?sm=d#0]

2) **Theme switching (blue/orange)**
- AI helped implement and debug theme persistence logic (e.g., using local storage and class toggling).
[https://www.perplexity.ai/search/how-to-save-results-of-button-.ciVvyUIREihwWnNiLYmKQ#0]

3) **Responsive layout + UI spacing fixes**
- AI supported CSS refinements for mobile/desktop layouts and fixing alignment/spacing issues.
[https://www.perplexity.ai/search/how-to-code-css-with-an-uneven-9aFZ5JlATWqRwa9RNiDMHQ#0]

4) 


## Testing

All testing for Dream was carried out **manually** by running through our user stories and verifying that each feature behaves correctly in realistic user flows. We focused on the “core journey” (login → dashboard → focus mode → buddy/quests → notes market → purchase → your notes → leaderboard → chat) and also tested edge cases such as empty inputs, broken network connections, and mobile responsiveness.

### Manual Testing Scenarios

1. **Create Account (Mascot → Theme)**
   1. Go to the **Create Account** page.
   2. Select the **Blue** study buddy, then enter a valid email and password.
   3. Submit and verify the app loads with the **blue theme** (buttons/accents/backgrounds).
   4. Repeat with the **Orange** study buddy and verify the **orange theme** applies site-wide.
   5. Refresh the page and verify the chosen theme persists (still shows the correct theme).

2. **Login**
   1. Go to the **Login** page.
   2. Enter email and password.
   3. Verify successful navigation to the next screen (e.g., Dashboard/Home).
   4. Try leaving fields empty and verify the page does not proceed until values are provided (if validation exists).

3. **Dashboard Navigation**
   1. Go to the **Dashboard** page.
   2. Click each primary CTA/entry point:
      - **Start Focus Mode**
      - **Study Buddy**
      - **Notes Marketplace**
      - **Your Notes**
      - **Leaderboard**
      - **Daily Spin**
   3. Verify each button routes to the correct page and returns properly using Back navigation.

4. **Focus Mode (Timer + Restricted Navigation)**
   1. Start a focus session from the **Dashboard**.
   2. Verify the **timer starts running** and updates correctly.
   3. Attempt to change pages using navigation.
   4. Verify **page switching is blocked** and only allowed sections are accessible:
      - **Notes**
      - **Timer**
      - **Study Buddy**
   5. End the session (if your UI allows) and verify normal navigation returns.

5. **Focus Mode Sound Design**
   1. While in Focus Mode, tap the **Sound** button.
   2. Select each sound option:
      - White noise, Lofi, Rain, Brown noise, Café ambience
   3. Verify the selected sound changes correctly.
   4. Test play/pause/stop (depending on your controls).
   5. On mobile, confirm sound only plays after a user tap (browser policy).

6. **Study Buddy (3D Model + Health Bar + Quests)**
   1. Go to the **Study Buddy** page.
   2. Verify the **Sketchfab 3D embed loads** and can be interacted with (rotate/drag).
   3. Verify the correct **model loads for the chosen theme**:
      - Blue theme → e_Low model
      - Orange theme → Baby White Rhino model
   4. Confirm **health bar is visible** and quest list is displayed clearly.

7. **Daily Spin**
   1. Go to the **Daily Spin** page.
   2. Spin the wheel.
   3. Verify a result is displayed (task or reward outcome).
   4. Refresh and confirm the page still loads correctly (daily limitation rules only if implemented).

8. **Notes Marketplace → Preview**
   1. Go to the **Notes Marketplace** page.
   2. Browse note listings and open at least 2–3 note previews.
   3. Verify the preview shows:
      - Note description
      - Reviews
      - Star ratings
   4. Verify the preview UI is readable and not cut off on mobile.

9. **Purchase Notes → Confirmation Feedback (Lottie)**
   1. From a Preview page, trigger a purchase.
   2. Verify the **purchase confirmation animation (Lottie)** plays.
   3. Verify the user receives clear success feedback (no ambiguity).
   4. Verify the UI continues smoothly after confirmation (no stuck state).

10. **Your Notes (PDF Access)**
   1. Go to **Your Notes**.
   2. Open a purchased note PDF.
   3. Verify the PDF loads correctly and is readable.
   4. Test with a larger PDF file (if available) to check loading time.

11. **Leaderboard (Google Sheets GViz Fetch)**
   1. Go to the **Leaderboard** page.
   2. Verify it displays ranking rows properly (name + hours).
   3. Verify ordering is descending by study hours and limited to top entries.
   4. Temporarily disconnect internet and reload the page:
      - Verify the error state appears (e.g., “Failed to load leaderboard”)
   5. Reconnect internet and verify it recovers after refresh.

12. **Chat (GC + DM)**
   1. Go to the **Chat** page.
   2. Open a Group Chat and verify messages load.
   3. Open a DM and verify messages load.
   4. Verify the layout remains usable on mobile (message panel and input not overflowing).

13. **Settings + Privacy / Parental Controls**
   1. Go to **Settings**.
   2. Verify all sections are visible and readable (account + privacy + parental controls).
   3. Test toggles/inputs if present and verify they respond correctly.

14. **Contact Us**
   1. Go to the **Contact Us** page.
   2. Try submitting an empty form and verify the form blocks submission or shows required-field feedback (if implemented).
   3. Try an invalid email format and verify the form rejects it (if implemented).
   4. Submit with valid inputs and verify a success confirmation is shown (if implemented).

### Browser and Screen Size Testing

We tested Dream on multiple screen sizes using both real devices and responsive testing tools:
- **Desktop:** Chrome (wide layout checks, side-by-side panels where applicable)
- **Mobile:** Chrome mobile emulation
- **Safari/iOS (if tested):** checked layout differences for iframes and fonts

Responsive checks included:
- Navigation remains accessible and not overlapping
- Buttons remain tappable on mobile (no cramped UI)
- Long content (marketplace previews, chat messages) wraps without overflow
- 3D embed scales correctly within its container

### Bugs / Issues Found During Testing

- **Network dependency for 3D and leaderboard:** The Sketchfab 3D buddy and Google Sheets leaderboard require internet access; on weak networks, loading can be slow or fail. We added clear loading and error states where possible.
- **Mobile audio behaviour:** Some mobile browsers block sound until the user taps play (browser autoplay restrictions). We ensured sound only starts after user interaction.
- **Iframe sizing differences:** On certain devices/browsers, iframe embeds may render with slightly different heights; we adjusted containers to reduce layout jumping.


## Credits
### Media
- the images from notes marketplace were AI generated my perplexity with detailed prompts
- the notes of enzyme kinetics were taken form [https://www.rose-hulman.edu/~brandt/Chem330/Enzyme_kinetics.pdf] sourced from google
- the background of the study buddy is sourced from pinterest

### Acknowledgements

- I received inspiration for this project from Study bunny app -- the avatar health bar and focus timer function
- I received inspiration for this project from Shopee with the daily spin the wheel