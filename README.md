[GOOD**DEED**](#top)

[Vision](#vision)[Features](#features)[App](#app)[Reputation](#reputation) [Safety](#trust)[Tech](#tech)[Business](#business)[Roadmap](#roadmap)[MVP](#mvp)[Validate](#validate)

Startup product blueprint · Android + iOS

# Make kindness the new *social currency.*

A social platform where people earn recognition by making a positive difference in someone else's life. It rewards genuine kindness, and the people being helped never become props for someone else's popularity.

Startup conceptAndroid + iOSHyderabad pilotProduct roadmap

Kindness chain, a V2 feature. One good deed can inspire many more.

01 · Product vision and identity

## Treat it as a real startup from day one

Before any code, define the product, its users, its business model, its safety principles, and how it differs from Instagram, Facebook and other social platforms.

Reward genuine kindness, not the performance of kindness.

The recognition system should motivate people to help, but the people receiving help must never become props for someone else's popularity.

### The problems we address

- People help strangers, but these actions often go unnoticed.
- Online recognition is not connected to positive social impact.
- People who need help don't know where to find willing helpers.
- No single community feed is focused on everyday kindness.

### HELP

People help strangers and contribute to their communities.

### SHARE

They share their experiences and inspire others.

### RECOGNIZE

The community recognizes genuine positive contributions.

Mission

To encourage everyday acts of kindness by making positive social contributions visible, appreciated and rewarding.

Vision

A world where helping others becomes as socially rewarding as gaining followers.

### Target audience

- College students and young adults
- People interested in volunteering
- Local community groups
- NGOs and charitable organizations
- Individuals who want to help people nearby

**Initial launch market: India**Start with one city or a few selected communities before expanding. Hyderabad is the proposed pilot.

02 · Product features

## Eight modules, built in stages

Filter by priority. Only the modules marked MVP ship in version 1.

A

### Social kindness feed

MVP priority

- Publish good deeds, with photos or video
- Write stories about helping strangers
- Appreciate, comment and share; follow people and communities
- Post fields: category, description, optional media, optional approximate location, verification, visibility

Users must be able to post without showing the recipient's face or revealing their identity.

B

### Help requests and offers

MVP priority

- Offer help, or request help from the community
- Categories: food, education, transport, medical, elderly, emergency, jobs and skills, volunteering
- Flow: request, community, helpers respond, requester chooses, help happens, marked complete, optional confirmation

Medical emergencies point to emergency services, not to a social platform.

C

### Kindness reputation system

Core differentiator

- Three separate measures: Good Deeds, Impact, Trust
- Badges based on transparent criteria, never purchased
- Never collapsed into one simplistic score

D

### Stranger verification

Essential trust feature

- Self-reported, recipient-confirmed, community-reviewed
- Private links or one-time codes, no public profile for recipients
- Never claim more verification than the evidence checked

E

### Kindness leaderboard

Basic version in MVP

- Weekly, monthly, city and community boards
- Anonymous recognition and most consistent helpers
- No ranking by money spent or popularity

A user can hide their ranking entirely.

F

### Kindness chain

Signature feature · V2

- Connect stories: one helped person later helps someone else
- Participation is optional
- No causal claim unless participants confirm the chain

G

### Anonymous kindness

Public or anonymous

- Share a deed without displaying identity
- Two post types: public recognition and anonymous contribution
- Recipients can request a story about them be removed or made private

H

### Daily kindness challenges

V2

- Help someone carry something
- Share food with someone in need
- Teach a useful skill, help an elderly person, donate unused books
- Repeat engagement without relying on likes and comments

03 · Application design

## Five tabs, one clear job each

Tap the tabs in the phone to move through the main screens. This is an illustrative interface concept, not a working application.

GOODDEED9:41

### Screen-by-screen specification

| Screen | Main functionality |
| --- | --- |
| Welcome | App introduction and onboarding |
| Sign up | Email, phone or supported social login |
| Home | Good deed feed |
| Explore | Find help requests and communities |
| Create | Publish a good deed or request |
| Post details | Story, comments, verification |
| Profile | Achievements and contributions |
| Leaderboard | Community rankings |
| Notifications | Likes, comments, confirmations |
| Settings | Privacy, security and account controls |

04 · Reputation system

## A contribution profile, not a single score

This is what differentiates the startup. If the reward system is poorly designed, GOODDEED becomes another platform where people stage activities for engagement.

Deeds

### Good Deeds

Number of recorded acts.

Impact

### Impact

Confirmed positive outcomes.

Trust

### Trust

Reliability and verification history.

Helping someone carry groceries should not count as less valuable than a ₹10,000 donation, which is why these are never combined into one number.

### Rules that keep the system honest

| Rule | Reason |
| --- | --- |
| No points for likes | Avoid popularity farming |
| No points for followers | Avoid influencer-style competition |
| No extra points for money spent | Prevent wealth-based ranking |
| Verification increases trust | Encourage genuine contributions |
| Repeated fake posts lead to penalties | Discourage manipulation |
| Anonymous deeds remain possible | Encourage selfless actions |

### Badges with transparent criteria

**First Kindness**First completed good deed

**Consistency Star**Regular positive actions

**Community Hero**Community contributions

**Trusted Helper**Consistent verified activity

Sample profile · fictional data

### Rahul Kumar

GOODDEED community member · Trusted contributor

**24**Good deeds

**18**Confirmed

**6**Badges

Initially there is no public numerical trust score. A transparent set of badges and verification labels is easier for users to understand. A verified deed earns recognition points; unverified posts stay visible without the same trust status.

05 · Verification, safety and legal

## Prove the help without exposing the person helped

The platform deals with strangers, vulnerable people, location information and images. Safety is not an optional module.

1

### Self-reported

The helper submitted the story.

2

### Recipient-confirmed

The recipient privately confirmed it.

3

### Community-reviewed

Trusted moderators reviewed supporting evidence.

### Verification safeguards

- Confirmation is never mandatory for receiving help.
- The recipient does not need a public profile.
- Private verification links or one-time codes can be used.
- Reported abuse triggers human review.
- Never claim a story is verified beyond the evidence checked.

### Ten essential safety requirements

1. Never publish someone's exact location automatically.
2. Never expose a recipient's personal information without permission.
3. Allow blocking and reporting.
4. Build human moderation tools.
5. Prevent harassment and exploitation.
6. Introduce safeguards for minors.
7. Protect private verification information.
8. Allow account deletion and appropriate data deletion.
9. Introduce spam and scam detection.
10. Provide a way to appeal moderation decisions.

### India-specific legal review

Get legal advice before launch on:

- Digital Personal Data Protection Act and applicable rules
- Information Technology Act and intermediary obligations
- Consumer protection requirements
- Content moderation and grievance processes
- Children's privacy and age-related safeguards
- Fundraising, payment and charitable solicitation rules, if donations are added later

**No money wallet in V1**Connect people and document non-financial assistance. Don't collect identity documents or sensitive recipient information without a clear legal and operational need.

06 · Technical architecture

## One codebase for Android and iOS

Avoid building two separate applications. Design the database before writing the app.

### Recommended stack

**React Native + Expo**Frontend · Android and iOS

**Supabase**Backend · auth, database, storage

**TypeScript**Logic and type safety

**Figma**Wireframes and UI design

**GitHub**Source code and version control

**GOODDEED mobile application**Android + iOS / React Native

↓

**Application services**Authentication · Posts · Help requests · Reputation

↓

**Supabase backend**PostgreSQL · Authentication · Storage · Realtime

↓

**Media storage**

**Notifications**

**Moderation**

**Analytics**

### Starting database tables

`users``profiles``posts``post_media``help_requests``help_responses``verifications``reactions``comments``follows``badges``user_badges``reputation_events``reports``notifications`

**Important engineering decision**Reputation is calculated from trusted backend events, not from numbers sent by the mobile app, otherwise someone could manipulate their score. Use database access policies so users only see what they are authorized to see.

### One complete interaction

| Step | What happens |
| --- | --- |
| 1 | Rahul creates an account and helps a stranger. |
| 2 | Rahul publishes a good deed. |
| 3 | The recipient receives a private verification request and confirms the help. |
| 4 | The backend records the verification and Rahul receives recognition. |
| 5 | The community discovers the story and someone else gets inspired. |

07 · Business model and market

## Build trust first, revenue second

Initially focus on a real community, not on generating revenue. Once there is traction, these streams are possible.

### Sponsored campaigns

Brands sponsor kindness challenges.

### NGO partnerships

NGOs run verified community campaigns.

### CSR partnerships

Companies support measurable social initiatives.

### Community programs

Organizations run volunteering programs.

### Premium organization tools

Advanced dashboards and campaign management.

**Example: "Feed 10,000 people this month"**A company sponsors, NGOs coordinate, volunteers participate, GOODDEED tracks verified outcomes. The company gets an impact report, the community gets recognition.

Sponsored campaigns must be clearly labelled, and commercial partners must not be able to buy individual users' reputations.

### Competitor differentiation

| Platform | Main focus | GOODDEED's distinction |
| --- | --- | --- |
| Instagram | Content and creators | Real-world kindness |
| Facebook | Social connections and communities | Help and contribution |
| LinkedIn | Professional reputation | Social contribution reputation |
| Volunteer platforms | Organized volunteering | Everyday individual acts of kindness |

**Strongest differentiation:** a social reputation system connected to real-world positive actions. Don't claim no similar products exist; research existing kindness, volunteering and social-impact platforms and validate the market gap before investing heavily.

### Launch strategy

1

### Private prototype

Test every major feature with a small group.

2

### Closed testing

50–100 people. Do they share deeds? Are recipients comfortable verifying?

3

### Local pilot

300–500 users via colleges, community groups and NGOs.

4

### Public launch

Open registration after safety, moderation, privacy and usability are resolved.

5

### Expansion

New cities once the first shows repeat usage and real outcomes.

### First-user channels

- College ambassador programs
- NGO partnerships
- Instagram educational content
- Local volunteering communities
- Monthly kindness campaigns

The launch should create real-world stories, not just social media advertisements.

08 · Implementation roadmap

## Sixteen weeks, seven phases

Indicative timeline for a solo beginner working consistently. These are planning estimates, not delivery dates. Moderation, iOS testing and launch preparation may take longer.

1 Research

2 UI/UX

3

4 Core app

5 Impact

6 Safety

7 Pilot launch

Phase 1 · Product research Weeks 1–2

- Finalize the name and branding
- Research similar applications and interview potential users
- Validate the problem, write product requirements, finalize the MVP

Phase 2 · UI/UX design Weeks 3–4

- Wireframes in Figma: onboarding, home feed, post creation, profiles, leaderboard
- Create a clickable prototype

Phase 3 · Development setup Week 5

- Install Node.js, VS Code and Expo; create the React Native project
- Set up Git and GitHub; create the Supabase project

Phase 4 · Core application Weeks 6–8

- Registration and login, profiles, home feed
- Create good deed posts, image uploads, comments and reactions

Phase 5 · Social impact features Weeks 9–10

- Help requests and offers, verification
- Reputation events, achievement badges, basic leaderboard

Phase 6 · Safety and testing Weeks 11–12

- Reporting and blocking, moderation dashboard, privacy controls
- Security testing, Android and iOS testing, bug fixes

Phase 7 · Pilot launch Weeks 13–16

- Invite initial users, collect feedback, measure engagement
- Observe verification issues, improve the product, prepare public launch

09 · Version 1 scope

## Be strict about what ships first

Don't build all eight modules at once. This is enough to demonstrate the core business concept without months on unnecessary features. Tick items off as you build them.

**Must-have features**0 of 13 complete · 0%

### Save for V2

`Kindness chains``Daily challenges``Advanced AI moderation``Organization dashboards``Advanced analytics``Sponsored campaigns`

### Estimated development budget

| Item | Initial approach |
| --- | --- |
| Figma design | Free tier |
| React Native + Expo | Free development tools |
| Supabase | Free tier initially |
| GitHub | Free tier |
| Domain | ₹800–₹1,500 per year, approximately |
| Initial cloud services | Free tier initially, then usage-based |
| Testing devices | Use existing devices where possible |
| Legal and compliance | Obtain professional quotes |

Rough planning estimates, not vendor quotes. A public platform eventually needs budget for infrastructure, moderation, security, support and legal compliance. Free tiers won't carry a growing production platform, and app store publishing has developer account fees.

### Biggest risks to solve before launch

| Risk | Our solution |
| --- | --- |
| Fake good deeds | Verification and moderation |
| People exploiting recipients for videos | Consent-first posting rules |
| Fake help requests | Trust controls and reporting |
| Harassment | Block, report and moderation |
| Popularity manipulation | No points for likes or followers |
| Dangerous meetups | Private messaging safeguards and safety guidance |
| Privacy breaches | Data minimization and access controls |
| Low user engagement | Challenges, community campaigns and kindness chains |

Users should also be able to report a staged, misleading or exploitative good deed without publicly confronting the person who posted it.

10 · Success metrics and validation

## Measure outcomes, not downloads

Don't judge the startup only by downloads. If users only post once to gain popularity, the platform isn't achieving its mission, so the share of people who return to help again matters most.

North-star metric

### Verified positive outcomes per active user

| Metric | What it tells us |
| --- | --- |
| Monthly active users | Community size |
| Weekly active users | Engagement |
| Good deeds submitted | Participation |
| Recipient confirmation rate | Trust |
| Help requests completed | Real-world usefulness |
| Repeat helpers | Retention |
| Reports per 1,000 posts | Safety |
| Time to fulfill help requests | Community responsiveness |

### Validate before coding

Confirm people actually want this. Interview at least 15–20 potential users, and ask whether they would actually use it, not whether they like the idea.

**20**user interviews

**10**people to test the prototype

**5**organizations or groups contacted

**1**clickable prototype

**1**full help-to-confirmation journey tested

### Interview questions

1. Have you ever helped a complete stranger?
2. Would you share that experience on a social platform?
3. Would you use an app where people are recognized for helping others?
4. Would you feel comfortable confirming that someone helped you?
5. Would you use an app to find people nearby who need assistance?
6. What would make you trust or distrust this platform?

### Build in this order

1. **Product Requirements Document.** Every feature, screen, user role and business rule.
2. **Brand identity.** Name, logo, colors, typography. Check trademark and domain first.
3. **UI/UX prototype.** Interactive in Figma.
4. **Database and backend.** Supabase tables, security policies, logic.
5. **Application development.** React Native and Expo.
6. **Testing and pilot.** Real users and community organizations.
7. **Launch and growth.** Start locally, measure impact, expand.

Direction A

### Social media first

People share good deeds, build profiles, gain recognition and inspire others. Help requests are an additional feature.

Direction B

### Social impact first

People find those who need help, connect with helpers, complete real-world assistance, then share their experiences.

**Recommendation: a hybrid**The social feed is the entry point, and actual assistance is the central measure of success. That gives people a reason to join while ensuring the platform creates real value.

GOOD**DEED**

**Next milestone:** a complete Product Requirements Document covering every screen, button, feature, user journey, database requirement, API requirement and business rule. It becomes the master document through development.

GOODDEED startup blueprint · November 2026 · Planning estimates only
