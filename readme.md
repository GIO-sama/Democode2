 
 
 
 
BUHAY BOARDING 
Full Product Masterplan 
Burauen, Leyte — Exclusive Edition 
 
 
Version 1.0  |  Confidential  |  2025 
 
 
 
What this document is 
This is the complete blueprint for designing, building, launching, growing, and sustaining a boarding house finder app exclusive to Burauen, Leyte. It covers product philosophy, feature design, technical architecture, phased rollout, marketing, risk management, and success metrics. Every section is written to be actionable, not theoretical.  
01 — Problem & Local Context 
 
 
The Actual Problem 
Finding a boarding house in Burauen today means one of three things: scrolling through inconsistent Facebook posts, cold-messaging strangers, or physically walking under the sun knocking on doors asking 'may bakante po ba?' None of these scale. None of them give you reliable information. And none of them protect you from wasted time. 
Landlords face the mirror image of this chaos. They answer the same five questions over and over. They deal with tenants who arrive with wrong expectations because the listing on Facebook was three years old. They have zero tool to manage inquiries, set expectations, or filter tenant fit.  
Why Burauen Specifically 
Burauen has two institutions generating boarding house demand: Eastern Visayas State University (EVSU) Burauen Campus and Burauen Community College (BCC). These are not massive universities — and that is exactly the point. A smaller, tight community means: 
•	Word of mouth travels faster and is more credible 
•	One good landlord endorsement unlocks several others 
•	You can manually verify every listing without needing automation 
•	Students from outside Leyte are especially vulnerable to bad information — they cannot walk the streets to verify 
•	The competitive landscape is essentially zero — no tech product targets this market 
 
The Opportunity Gap 
Problem 	Current 'Solution' 	What's Missing 
Find available rooms 	Facebook posts 	Real-time availability 
Know the real rules 	Ask the landlord verbally 	Written, structured info 
Contact without anxiety 	Cold call or cold message 	Low-stakes first contact 
Schedule a visit 	Manual back-and-forth texts 	Simple time booking 
Stay informed as tenant 	Group chats (chaotic) 	Landlord-only announcements 
Know when vacancy opens 	Check Facebook repeatedly 	Waitlist notification 
 
02 — App Identity & Core Philosophy 
 
 
Name 
Buhay Boarding 
"Buhay" means life in Filipino. It also doubles as a play on the lived reality of boarding house life — practical, grounded, alive. 
 
What It Is 
A boarding house directory for Burauen with a built-in communication layer. The directory is the product. The communication layer is the infrastructure. Everything else is secondary. 
 
What It Is Not 
•	Not a social media app 
•	Not a real estate platform 
•	Not a game 
•	Not a marketplace for anything other than finding a room 
•	Not an open community anyone can join freely 
 
Core Design Principles 
1. Landlord trust is the foundation 
Without landlords, you have no listings. Without listings, you have no seekers. Every feature decision must pass one test: does this make landlords more likely to trust and use the app? 
2. Friction reduction over feature addition 
Every time you add a feature, you add friction somewhere. A seeker asking about a room should face the minimum number of steps possible. A landlord responding should face even fewer. 
3. Information before interaction 
Before anyone sends a message, they should already know price, rules, curfew, utilities, and room availability. Messages should clarify specifics, not ask basics that should already be visible. 
4. Real always beats virtual 
The app exists to make a real-world decision — renting a room — easier. Virtual lounges, avatars, and social features exist only insofar as they lower the anxiety barrier to taking real action. The moment virtual features compete with real utility, remove them. 
5. Small and sharp beats big and dull 
Every phase has a hard stop. Features get added only when there is user evidence that they are needed, not because they sound good in a pitch deck.  
03 — Complete Feature Set 
 
 
For Seekers (People Looking for Rooms) 
Location-Based Directory 
On opening the app, seekers see a list of verified boarding houses sorted by proximity to either EVSU or BCC (selectable). No map needed at MVP — proximity is shown as a text label: '3minute walk from EVSU gate.' A map can be added in Phase 3 if users actually want it. 
Room Snapshot Card 
Each listing shows a scannable card visible before tapping into any lounge or profile. Card contains exactly: 
•	Monthly price (with utilities breakdown if applicable) 
•	Curfew time 
•	Allowed / not allowed list (visitors, pets, cooking, laundry on-site) 
•	Number of currently available rooms 
•	Distance from school 
•	Last verified date 
This card alone answers 90% of what a seeker needs to decide if this house is worth pursuing. 
 
Photo Gallery 
Real photos, taken at the time of verification, labeled by room type: single, double, shared CR, common area. No stock photos. No AI-generated images. If a landlord does not have photos, the app does not list them as verified — pending photo documentation only. 
Structured Inquiry Form 
When a seeker taps 'Ask a Question,' they do not get a free-form chat window. They get a short form: 
•	Name 
•	School (EVSU or BCC) 
•	Course and year level 
•	Target move-in date 
•	Specific question (optional free text, 200 char max) 
The landlord receives this as a structured notification — not a random text. This eliminates the 'pwede po bang mag-inquire?' message that gives landlords zero useful information. 
 
Visit Scheduler 
After inquiry, the seeker sees a simple calendar of time slots that the landlord has marked available for visits. Seeker picks one. Landlord gets a notification. One confirmation tap from the landlord locks the slot. No back-and-forth. No 'text me what time works for you.' 
Waitlist 
If a house is fully occupied, the 'Ask a Question' button changes to 'Join Waitlist.' Seeker taps it and is added to a queue. When a room opens, landlord taps one button to notify the entire waitlist simultaneously. Waitlist position is visible to the seeker. 
Filter System 
Seekers can filter the directory by: 
•	Price range 
•	Curfew time 
•	Utilities included (yes/no) 
•	Cooking allowed (yes/no) 
•	Visitors allowed (yes/no) 
•	Proximity to school (EVSU or BCC) 
•	Availability (show only houses with open rooms) 
  
For Landlords 
Listing Management Dashboard 
Web-accessible and mobile dashboard. Landlord can: 
•	Update room availability in one tap (rooms available: 0-10+) 
•	Edit price and rules at any time with change-log visible to seekers 
•	Upload or update photos 
•	Enable or disable the inquiry form 
•	Enable or disable the waitlist 
•	View and manage visit schedule slots 
 
Structured Inquiry Inbox 
All inquiries arrive in one inbox, formatted with seeker information already filled in. Landlord can mark each as: Replied, Interested, Not a Fit, Visit Scheduled, Room Offered, Declined. This gives landlords a CRM-lite view of their pipeline without calling it a CRM. 
Announcement Channel (Tenant-Facing) 
Landlords can post announcements to their current verified tenants only. Tenants receive push notifications. Announcements are read-only — tenants cannot reply within the app. Examples: 
•	Water interruption tomorrow 8AM–12PM 
•	Rent due this Friday — please pay to Gcash XXXX 
•	Gate will be locked at 9PM during midterms week 
•	Inspection Saturday 10AM, please clean common areas 
 
Visit Slot Management 
Landlord sets recurring available hours for visits (e.g., MWF 2PM–5PM) or adds one-time slots. Confirmed visits show on a simple calendar view. Landlord can cancel a slot with a tap, and the seeker is automatically notified. 
Inquiry Analytics 
A simple weekly summary showing: how many people viewed the listing, how many submitted inquiries, what questions were asked most often, and what filter settings people used before finding the listing. This is not a complex analytics dashboard — it is a one-page summary that helps landlords understand what matters to seekers. 
House Rules Editor 
A structured form (not a blank text box) for house rules. Categories: curfew, visitors policy, laundry policy, cooking policy, noise policy, payment terms, move-in requirements. Each has a dropdown or short text field. This standardizes rule display across all listings. 
 
For Current Tenants 
Tenant Verification 
When a seeker successfully rents a room, the landlord marks them as a verified tenant in the app. The seeker's account unlocks tenant-only features for that specific house. If they leave, the landlord removes them. This is manual and intentional — automated tenant verification is a Phase 3 problem. 
Announcement Feed 
Read-only feed of the landlord's announcements. Push notifications enabled by default, with per-category mute options. Tenants can mute reminder-type announcements (e.g., rent reminders) without muting emergency announcements. 
House Info Reference 
Tenants see a permanent reference page for their boarding house: landlord contact, house rules, payment instructions, emergency contacts, and wi-fi credentials (if landlord chooses to share). No more screenshotting the group chat every enrollment period. 
Optional: Inquiry Helper 
A very limited feature where a current tenant can flag a seeker's inquiry with a simple 'I can answer this' signal — not post an answer publicly, but notify the landlord that they are willing to be introduced to the seeker for a quick real-world conversation. The landlord approves this introduction. All of this is opt-in and landlord-controlled. 
This addresses the liability issue: tenants never speak publicly for the house. They only signal willingness to help, and the landlord decides. 
 
03B — Landlord Command Center 
 
 
The standard landlord dashboard covers listings, inquiries, and announcements. But the bigger opportunity is turning the app into a genuine business tool for boarding house operators — something that saves them money and mental energy, not just inquiry management. This section covers the full suite of landlord-side business features and their implementation priority. 
 
Philosophy 
Everything here ties back to four things: save time, save money, reduce mental load, give confidence. No fancy charts landlords won't understand. No AI predictions. No stock market tickers. Just tools that match how small landlords in Burauen actually think and work. 
 
 
1. Income & Financial Summary 
What It Shows 
A clean card at the top of the landlord dashboard showing at a glance: total collected this month, total pending, and how many rooms have paid out of total. A 'View breakdown by room' link expands into the full ledger. 
 
THIS MONTH 
₱12,500  Total Collected 
₱8,500   Pending 
3/5 Rooms Paid 
└─ View breakdown by room 
 
Deeper Features 
•	Per-room ledger: table showing each tenant, rent amount, paid status, and last payment date 
•	Payment history: calendar view of when payments came in — helps landlords spot chronic late payers 
•	Projected income: what they should collect if all rooms are at full capacity 
•	Year-over-year comparison: 'Same month last year you collected ₱11,200' — reveals trends without requiring a spreadsheet 
Why Landlords Need This 
Most small landlords in Burauen track payments on notebooks or pure mental math. They forget who paid, avoid confrontation, and sometimes undercount their own income. A simple ledger eliminates the awkward 'magkano na ba utang mo?' conversation. It also makes tax documentation — if they ever need it — significantly easier. 
 
2. Expense Tracker 
The Problem Landlords Don't Say Out Loud 
They know rent comes in, but they rarely track where it goes — repairs, water bills, new mattresses, replacement faucets. At the end of the year, they cannot tell if they actually profited. Some landlords are effectively subsidizing their tenants' low rent without knowing it. 
The Feature 
•	Expense categories: Repairs, Utilities, Supplies, Labor, Improvement 
•	Add expense in 3 taps: Amount + Category + Date (optional photo of receipt) 
•	Monthly and quarterly summary: 'You spent ₱3,200 on repairs this quarter' 
The Insight It Unlocks 
A landlord might discover they spend ₱2,000 per month on water bills because of a slow leak in one room. Or that repairs for their cheapest room ate up three months of its rent. The app is not just tracking — it is teaching them to run their boarding house like a business, not a favor. 
 
3. Vacancy Cost Calculator 
The Feature That Creates Urgency Without Nagging 
Displayed right next to the available rooms count, this shows the real cost of an empty room in language that lands. 
 
Vacancy cost this month: ₱3,500 
(2 rooms empty x 15 days x ₱233/day) 
Equivalent to: 8 kilos of rice  |  3 electric fans  |  1 month of internet 
 
Why This Works 
Abstract numbers do not move people to action. '₱3,500 lost' is easy to rationalize. '8 kilos of rice' is not. Translating vacancy cost into everyday equivalents creates urgency without any pressure from the app. The result: landlords update availability faster, respond to inquiries more promptly, and may consider minor price adjustments during slow seasons — entirely on their own initiative. 
 
4. Digital Collection Tracker + Payment Reminders 
Current Reality 
Landlords text tenants one by one asking 'Bayad na po ba?' Tenants reply late, forget, or ignore. Landlords feel like naggers. Tenants feel harassed. The relationship deteriorates over something administrative. 
The Feature 
•	One-tap 'Send payment reminders' to all tenants with rent overdue 
•	Tenants receive: 'Rent due tomorrow — GCash: 0917xxxxxx | Amount: ₱1,500' 
•	Optional: landlord can see who opened the reminder 
•	When a tenant marks themselves as paid, landlord gets a notification to confirm 
Why It Saves Time 
Instead of 12 individual messages, one tap. Instead of asking 'Sino nakapagbayad na?' every week, the dashboard shows you in a grid. The landlord becomes a manager, not a chaser. 
 
5. Maintenance Request Tracker 
The Hidden Time Sink 
Tenant tells landlord about broken faucet. Landlord mentally notes it. Forgets. Tenant follows up. Landlord says 'sige, check ko.' Cycle repeats for weeks until something breaks badly. This is not laziness — it is the natural result of having no system. 
The Feature 
•	Tenants submit maintenance requests via app: simple form with What's broken + optional photo 
•	Landlord dashboard shows: Pending (2) | In Progress (1) | Completed this month (5) 
•	Landlord can add a note: who is handling it, when it will be fixed 
•	Tenant receives notification when status changes to In Progress or Completed 
Cost Efficiency Insight 
Landlords can see repair patterns per room. If one room has had three repair requests in two months, that is a signal the room needs renovation, not repeated patches. Renovation once is cheaper than recurring repairs. The tracker makes this pattern visible. 
 
6. Seasonal Pricing Suggestions 
The Insight 
Demand spikes during enrollment in June and drops during semester breaks in December. Most Burauen landlords set a price once and never revisit it, either leaving money on the table during high demand or losing tenants during low season. 
How It Works 
Simple push notification sent two weeks before enrollment season and two weeks before semester break, based on the school calendar the admin maintains: 
 
High Season Notification 	Low Season Notification 
Enrollment starts in 2 weeks. Last year you were fully booked at ₱1,500/room with 12 inquiries in the first week. Demand will be high — no need to discount. 	Vacancies usually last 3 weeks in December. Consider: short-term rental options, or a small discount for 6-month advance payment. 
 
The app does not tell landlords what to do. It gives them their own historical data to decide. That is the difference between an annoying app and a useful advisor. 
 
7. Tenant Quality Indicator 
What It Is 
A private, landlord-only view of simple signals about a tenant's fit — not a punitive score, just useful context for landlords managing multiple rooms. Signals include: payment consistency (if tracked in app), length of stay, and whether they arrived via referral or cold inquiry. 
Critical Guardrails 
•	Tenants never see this — it is landlord-only and marked clearly as such 
•	No algorithmic scoring. Just raw data: '3 late payments in 6 months' or 'Referred by another tenant' 
•	Landlord interprets the data. The app does not label tenants as good or bad. 
•	Data is never shared between landlords. It is per-property and private. 
For landlords with two or three properties, this makes tenant renewal decisions easier without requiring memory or notebooks. 
 
8. Document & Contract Storage 
The Problem 
Boarding house contracts in Burauen live in Messenger chats, photocopied under desks, or in the landlord's memory. When a dispute arises — which it will — neither party can find the original agreement. 
The Feature 
•	Upload contract photo or PDF, linked to a specific tenant and room 
•	Expiration alerts: 'Contract for Room 2 ends in 30 days — renew or note move-out' 
•	Basic template generator: a customizable boarding house agreement landlords can fill out in the app, download as PDF, and print 
Time Saved 
No more 'saan ko ba nilagay yung kontrata ni Juan?' panic before a dispute. No more forgetting to renew and accidentally having a tenant stay without any written agreement for months. For landlords, this is peace of mind packaged as a feature. 
 
9. Water & Electricity Bill Splitter 
The Math Problem Landlords Hate 
Submeters exist in some boarding houses, but calculating individual shares is manual, errorprone, and a frequent source of tenant disputes. Some landlords just divide equally — which is fair in theory but creates resentment when one tenant uses significantly more electricity than others. 
The Feature 
•	Landlord enters total bill amount and due date 
•	Enter submeter readings per room — or tenants submit their own readings via the app 
•	App calculates each tenant's share and generates a breakdown 
•	Each tenant sees: 'Your share this month: ₱450 (based on 35 kWh usage)' 
•	Landlord marks who has paid, with the same one-tap reminder system from Feature 4 
Why It Is Cost-Efficient 
It reduces arguments. Arguments take time. Time is money. It also prevents the situation where a tenant refuses to pay because they do not understand the computation — the breakdown is visible, verifiable, and sent directly to them. 
 
10. The Landlord Command Center (Dashboard Summary) 
All features above converge into a single dashboard view that greets the landlord with everything they need to know, requiring no navigation to find the most urgent items. 
 
GOOD MORNING, MARIA 
Your 3 properties  •  Burauen 
┌─ TODAY'S SNAPSHOT ──────────────┐ 
│  ₱8,200 collected this week       │ 
│  2 vacancies  •  12 tenants       │ 
│  1 pending maintenance request    │ 
└──────────────────────────────┘ 
 [R1: Paid] [R2: Paid] [R3: Pending] [R4: Empty] 
┌─ QUICK ACTIONS ──────────────┐ 
│  [Send rent reminders]            │ 
│  [Add new expense]                │ 
└──────────────────────────────┘ 
┌─ THIS MONTH'S INSIGHT ─────────┐ 
│  Vacancy cost this month: ₱1,200  │ 
│  (2 empty rooms for 8 days)       │ 
└──────────────────────────────┘ 
  
Implementation Priority 
Build these in order. Each one delivers standalone value, so landlords benefit immediately rather than waiting for the full suite. 
 
# 	Feature 	Why First 
1 	Income summary + per-room ledger 	Solves the #1 mental pain point — who paid and who didn't. 
2 	Payment reminders (one-tap) 	Saves time immediately, reduces landlordtenant friction. 
3 	Expense tracker 	Small development effort, enormous insight value. 
4 	Maintenance request tracker 	Makes tenants self-service; removes landlord as middle-man. 
5 	Vacancy cost calculator 	Changes landlord behavior without any direct pressure. 
6 	Bill splitter (water/electricity) 	Reduces the most common source of tenant disputes. 
7 	Contract storage + templates 	Peace of mind. Low development cost, high perceived value. 
8 	Seasonal pricing suggestions 	Only useful after you have 2+ full seasonal cycles of data. 
9 	Tenant quality indicator 	Only after payment tracking is stable and consistent. 
 
The Future Revenue Path (Not Now — But Real) 
If landlords are tracking income, expenses, and collecting rent through reminders in one place, a natural Phase 5 or 6 feature presents itself: 
Future Monetization Seed 
'Would you like tenants to pay rent directly through the app? Automated recording, no chasing, no missed payments. 1% transaction fee, deducted automatically.' This is not built now. Trust is built first. Tools are built second. Transactions come third — and only when landlords already depend on the app enough that convenience outweighs the fee. 
Do not mention this to landlords during acquisition. It is a future option, not a current promise. Build the free tools so well that paying 1% later feels like a bargain. 
04 — Technical Architecture 
 
 
Design Philosophy 
Build the minimum viable technical stack. Every technology choice should be justified by a specific product requirement, not by what looks impressive on a resume or portfolio. Studentfeasible, not Silicon Valley fantasy. 
 
Frontend 
Layer 	Technology 	Why 
Mobile App 	Flutter 	Single codebase for Android + iOS. Large community, fast rendering, works offline. 
Admin Dashboard 	React (web) 	Landlord dashboard accessed via browser — no need to install an app. 
Avatars / Visuals 	Lottie + 2D assets 	Lightweight animations without 3D overhead. 
Cartoonish but not game-like. 
Mapping (Phase 3) 	Google Maps Flutter Plugin 	Only when map is confirmed needed by users. Add later. 
 
Backend 
Layer 	Technology 	Why 
Database 	Supabase (PostgreSQL) 	Open source, free tier, built-in auth, row-level security. Easier than raw Firebase for relational data. 
Authentication 	Supabase Auth 	Email + password for MVP. Phone/OTP in Phase 2. 
Real-time 	Supabase Realtime 	For announcement push and 
inquiry notifications. Not for full chat — no open chat channels. 
File Storage 	Supabase Storage 	For listing photos and house documents. 
Push Notifications 	Firebase Cloud Messaging 	Industry standard, free, Flutter plugin available. 
 
Database Schema Overview 
Core tables only — do not build what you don't need at launch. 
 
users 
id, email, display_name, role (seeker | tenant | landlord | admin), school (EVSU | BCC | other), course, year_level, created_at 
boarding_houses 
id, landlord_id (FK users), name, address, distance_evsu_minutes, distance_bcc_minutes, price_min, price_max, curfew_time, rules_json, available_rooms, total_rooms, verified (bool), verified_date, verified_by, is_active 
room_snapshots 
id, house_id (FK), room_type (single|double|shared), price, description, photos_json inquiries id, house_id, seeker_id, name, school, course, year_level, target_date, specific_question, status 
(pending|replied|interested|not_a_fit|visit_scheduled|offered|declined), created_at visit_slots 
id, house_id, date, time_start, time_end, is_available, booked_by (FK users nullable), created_at waitlist 
id, house_id, seeker_id, position, notified (bool), created_at tenants 
id, house_id, user_id, move_in_date, is_active, added_by (landlord id), created_at 
announcements 
id, house_id, landlord_id, title, body, category (reminder|emergency|info|activity), created_at 
 
Security & Access Control 
Role-based access is the backbone. Supabase Row Level Security (RLS) enforces this at the database level, not just the application level. 
•	Seekers: can view listings, submit inquiries, join waitlists, book visit slots 
•	Tenants: all seeker permissions + view announcements for their house + view house info reference 
•	Landlords: manage their own listings, inbox, visit slots, announcements, and tenant roster only 
•	Admin (you): verify listings, remove bad actors, view all data for oversight 
 
Offline Behavior 
Listing data is cached locally on the device so that seekers can browse even with poor connection (common in Burauen). Inquiry submission and visit booking require connectivity — if offline, the app queues the action and sends when reconnected. 
MVP Technical Scope 
What to build first 
Authentication → Listing creation (landlord) → Listing display (seeker) → Inquiry form submission → Inquiry inbox (landlord) → Waitlist → Visit slot booking. That is the complete MVP. Everything else is Phase 2 or later.  
05 — UI/UX Design Philosophy 
 
 
Overall Aesthetic 
Clean, warm, and trustworthy. Not a game. Not a dating app. Not corporate. Think a welldesigned school bulletin board brought to mobile — organized, easy to scan, friendly without being childish. 
 
Color Language 
Color 	Usage 	Why 
Navy / Deep Blue 	Primary headers, CTA buttons 	Trustworthy, serious, landlordfriendly 
Warm White / Light Gray 	Background 	Easy on the eyes in tropical sunlight 
Green 	Available status, confirmed actions 	Universal 'go' signal 
Amber / Yellow 	Waitlist, pending status 	Caution without alarm 
Red 	Full / unavailable / warning 	Clear stop signal 
 
Typography 
One font family. Nunito or Poppins — both are rounded, friendly, highly legible on mobile, and free. Large base font size (16pt minimum) because many users will be reading in outdoor light on budget Android phones. 
 
Avatar System 
Simple 2D cartoon avatars for seeker profiles only. Purpose: reduce the anxiety of a first contact by making the seeker feel less exposed than a real photo. Avatars are chosen at onboarding from a preset collection (10-15 options). No avatar customization system in MVP — that is scope creep. 
Landlords and their listings use real photos only. This is non-negotiable. The avatar is for the seeker's comfort; the listing must remain grounded in reality. 
 
Key Screens 
Screen 1: Home / Directory 
Top: school selector (EVSU | BCC). Below: filter bar (horizontal scroll). Main area: listing cards in a vertical list. Each card shows the Room Snapshot info. No map on this screen in MVP. 
Screen 2: Listing Detail 
Photos (full-width gallery). Room Snapshot card repeated in full. House rules section (structured, not a wall of text). Inquiry button or Waitlist button depending on availability. Visit slots button. 
Screen 3: Inquiry Form 
Short, structured form. 5 fields. One free-text area. Submit button. Confirmation screen that sets expectations: 'Your inquiry was sent. Landlords typically respond within 24 hours.' 
Screen 4: My Inquiries 
A list of the seeker's submitted inquiries with status indicators. This prevents repeated inquiries to the same landlord and gives seekers visibility into where they stand. 
Screen 5: Landlord Dashboard 
Available rooms counter (big, tapable to update). Inquiry inbox. Waitlist view. Announcement composer. Visit calendar. Listing editor. All accessible from a bottom nav or sidebar. 
Screen 6: Tenant Home 
Announcement feed for their house. House info reference. Optional inquiry helper toggle. 
 
Accessibility 
Large tap targets (minimum 48x48dp). High contrast text. Screen reader compatible labels on all interactive elements. No critical information conveyed through color alone. 
06 — Phased Rollout Plan 
 
 
Governing Rule 
Each phase must demonstrate stable, active usage before the next phase begins. Do not move to Phase 2 because you finished building it — move to Phase 2 because Phase 1 is being used regularly by real people. 
 
Phase 0: Pre-Launch (Before Writing Code) 
Duration: 2-4 weeks. This phase is the most important and easiest to skip. Do not skip it. 
 
Landlord Research 
Visit or message 8-10 boarding house landlords in Burauen. Do not pitch the app. Ask one question: 'Ano ang pinakamalaking problema ninyo pagdating sa bagong tenants o mga nagtatanong?' Document their answers word for word. These answers tell you what features actually matter. 
Seeker Research 
Ask 15-20 current students who live in boarding houses: 'Paano kayo nakakita ng boarding house? Ano ang pinakamahirap na part?' Document everything. 
Minimum Viable Commitment 
You need at least 3 landlords who verbally commit to listing their property on launch day before you write a single line of code. Not one. Three. If you cannot get three, the market is telling you something. Listen to it. 
Define Geographic Scope 
Walk or bike the main boarding house clusters in Burauen — near EVSU gate and near BCC. Mark the approximate clusters. This becomes your initial map coverage area and also tells you how many listings you can realistically verify manually. 
 
Phase 1: MVP Launch 
Duration: 8-12 weeks development + 4 weeks soft launch. 
Features included: 
•	Seeker registration and login 
•	Landlord registration and login 
•	Listing creation by landlord 
•	Room Snapshot card display 
•	Photo gallery 
•	Structured inquiry form 
•	Inquiry inbox for landlords 
•	Waitlist (join and notify) 
•	Visit slot scheduling 
•	Manual verification process (you visit and verify) 
 
Soft Launch Protocol 
Launch with exactly 3-5 verified listings. Invite seekers from EVSU and BCC only — use your professor connection, campus bulletin boards, and word of mouth. Do not do public marketing yet. You want controllable early adopters, not viral chaos before the product is stable. Success Criteria for Phase 1 
Metric 	Target 
Verified listings active 	3-5 
Inquiries submitted in first 30 days 	20+ 
Landlord satisfaction (self-rated) 	At least 2 of 3 say 'mas maginhawa' 
Visits scheduled through app 	5+ 
Rooms rented via app-assisted contact 	2+ 
  
Phase 2: Tenant Layer 
Trigger: Phase 1 criteria met. At least 5 tenants have successfully rented via app contact. 
Features added: 
•	Tenant verification by landlord 
•	Tenant announcement feed (read-only) 
•	House info reference page for tenants 
•	Inquiry status tracking for seekers 
•	Landlord inquiry analytics (weekly summary) 
•	Push notifications for announcements, visit confirmations, waitlist updates 
 
Goal of Phase 2 
The app becomes valuable to people who have already found a room. This is critical for longterm retention and word of mouth — tenants who use the app daily become the best advocates to future seekers. 
Success Criteria for Phase 2 
Metric 	Target 
Verified listings 	8-12 
Active tenant accounts 	20+ 
Announcements posted per month 	10+ 
Push notification open rate 	30%+ 
 
Phase 3: Community Layer 
Trigger: Phase 2 criteria met. At least 10 active listings, stable usage for 60+ days. 
Features added: 
•	School event calendar integration (manual input by admin) 
•	Seasonal surge notifications (enrollment period alerts) 
•	Map view of listings (Google Maps plugin) 
•	Landlord-to-landlord referral: landlords can refer seekers to other houses when they are 
full 
•	Optional: Inquiry Helper feature (tenant-assisted, landlord-approved) 
 
What Phase 3 Is Not 
It is not a messaging platform. It is not a community forum. It is not a marketplace. Every feature added in Phase 3 should trace directly back to a specific, observed user need — not a feature idea from a pitch deck. 
 
Phase 4 (Future, Optional) 
Only if evidence supports it. Possibilities: 
•	Local services directory: food delivery, laundry, printing, near each boarding house 
•	Emergency broadcast channel: typhoon, class suspension, campus emergency alerts 
•	Expansion to adjacent municipalities if interest exists organically 
Hard Stop Rule 
Phase 4 does not begin until Phases 1-3 are all stable, actively used, and generating genuine user requests for Phase 4 features. Build what people ask for, not what sounds good.  
07 — Marketing Strategy 
 
 
Core Principle 
In a small city, trust is the only currency. You are not marketing an app — you are marketing trust in a tool that affects where someone sleeps. Every marketing action should build credibility, not generate hype. 
 
Pre-Launch: The Quiet Build 
Anchor Landlord Strategy 
Your IT professor's boarding house is your first listing. But do not position this as 'my professor helped me' — position it as 'I helped a landlord solve a real problem they had.' The story of the app is always about the landlord's problem, not your project. 
The 3-Landlord Minimum 
Spend your pre-launch time building this coalition. Visit them personally. Show them a working prototype on your phone. Ask them to be part of the founding group. Being first on a platform that could become the standard for Burauen is a real incentive — name it. 
 
Phase 1 Launch: Controlled Word of Mouth 
Campus Touchpoints 
Print simple tarpaulins at EVSU and BCC bulletin boards. Not 'Download our app.' Instead: 'Looking for a Boarding House Near EVSU? Check Verified Listings at [app link].' QR code links directly to the most relevant listings. Replace the tarpaulin every enrollment period. 
Professor Endorsement 
A single professor posting about the app in a class group chat reaches more relevant people than any social media campaign. Target professors of courses with the highest percentage of out-of-town students: engineering, nursing, education. One genuine endorsement per semester. 
Facebook Presence (Minimal) 
Create one Facebook page. Post nothing except: verified listing updates, room availability announcements, and enrollment period reminders. Do not try to be funny or viral. Be useful. That is enough. 
 
Phase 2 Launch: Tenant Network Effect 
The most powerful marketing moment is when a verified tenant tells their classmate from their hometown: 'I found my boarding house through this app — it was so much easier.' Engineer this moment. 
•	When a seeker confirms they found a room via the app, show a simple screen: 'Tell a classmate who might need this too' with a pre-written SMS or Facebook message to share. 
•	The message is always practical: 'Looking for a boarding house in Burauen? This app has verified listings with real photos and rules — [link]' 
 
Seasonal Marketing Calendar 
Period 	Seeker Activity 	App Action 
March-April 	High — enrollment approaching 	Push notification to all users: 'Enrollment season — check 
new listings' 
June-July 	Very High — semester start 	Refresh all listing photos, confirm availability with all landlords 
October-November 	Medium — mid-year transfers 	Waitlist reminder campaign: 
'Still looking? Join the waitlist' 
December-January 	Low — sembreak 	Update listings, onboard new landlords, improve features 
  
What NOT to Do 
Avoid These Marketing Mistakes 
Do not run paid ads — your audience is too specific and too local for Facebook ads to be cost-efficient. Do not chase viral content — one misleading viral post can destroy the trust you've built. Do not open the platform to listings you haven't verified — one fake listing ruins credibility for all real ones. Do not promise features that don't exist yet.  
08 — Landlord Acquisition & Retention 
 
 
Why Landlords Require Special Attention 
Landlords are the supply side of your marketplace. Every feature in the app exists because landlords have listings. If you lose landlords, you lose everything. They must be treated as partners, not users. 
 
The First Conversation Script 
When approaching a landlord, never lead with 'I made an app.' Lead with their problem. 
“Ma’am / Sir, ilang beses na po kayong nasagot ng parehong tanong mula sa mga nagtatanong ng kwarto? Kumusta ang pag-manage ng mga bisita para sa house viewing? Mayroon po akong libre na tool na nagre-reduce ng ganung klase ng trabaho — gusto po ninyong makita?” 
Notice: no mention of tech, no mention of download, no mention of 'system.' Only their pain point, then a tool. Show the prototype on your phone immediately after. 
 
The Value Proposition Per Landlord Type 
Landlord Type 	Their Biggest Pain 	Your Pitch 
Tech-uncomfortable older landlord 	Repetitive inquiries, wasted time 	Focus on structured inbox and one-tap availability update 
Active Facebook user landlord 	Chaotic comment sections, lost messages 	Structured inbox beats 
Facebook DMs 
Landlord with frequent vacancies 	Finding good-fit tenants quickly 	Seeker profile info and waitlist 
Landlord with long waitlists 	Managing who's next fairly 	Waitlist queue with automatic notification 
 
Landlord Retention 
Acquisition is one conversation. Retention requires that the app actually saves time every single week. The announcements feature is your retention anchor — if a landlord uses it to notify tenants about rent due, they open the app at least once a month. That is enough to prevent churn. 
•	Send landlords a monthly summary: 'This month, your listing was viewed 47 times. 8 inquiries were submitted. 3 visits were scheduled.' 
•	When a new semester approaches, proactively message landlords: 'Enrollment season is coming — would you like to update your listing photos?' 
•	If a landlord goes 30 days without updating availability, send a gentle reminder: 'Is your availability count still accurate? Seekers are looking now.' 
 
Verification Process (Your Role) 
1.	Contact landlord, confirm they want to be listed 
2.	Visit the property in person (or with a trusted contact) 
3.	Take photos of: gate, common area, sample room, CR, kitchen/laundry if shared 
4.	Fill out the listing form together with the landlord 
5.	Confirm price, rules, curfew, and utilities verbally and in writing in the app 
6.	Mark as verified with today's date 
7.	Revisit or re-verify every semester — listings older than 6 months without update get a 'needs re-verification' badge  
09 — Risk Registry & Mitigation 
 
 
Risk Assessment Overview 
 
Risk 	Likelihood 	Impact 	Mitigation 
Anchor landlord drops out 	Medium 	High 	3-landlord minimum prelaunch; no single landlord is mission-critical 
App turns into gossip / drama space 	High 	Medium 	No open chat. Structured forms only. Tenant interactions require landlord approval. 
Inaccurate listing data damages trust 	Medium 	High 	Manual verification with reverification every 6 months. 
'Needs update' badge if stale. 
Landlords find app too complicated 	High 	High 	Web dashboard (no app install needed for landlords). 
Onboarding done by you, in person, for first 5 landlords. 
Low seeker adoption — app feels unnecessary 	Medium 	High 	Launch during enrollment season. First 10 users get personal onboarding from you. 
Fake or troll accounts 	Low 	Medium 	Require school email or referral code at signup. Admin can deactivate accounts. 
Market too small to sustain network effects 	High 	Medium 	Exclusivity is the strategy, not the limitation. Capture 80% of one small market rather than 1% of a big one. 
 
 
10 	Success Metrics & KPIs 
 
Measuring the wrong things will mislead you. These metrics are chosen because they reflect real value delivered to real people — not vanity metrics like download counts. 
 
Primary Metrics (The Ones That Actually Matter) 
Metric 	Target (6 months) 	Why It Matters 
Rooms rented via appassisted contact 	10+ 	This is the actual product outcome. Everything else is secondary. 
Landlords with active listings 	5-10 	Supply health. Below 5 = the directory is too thin to be useful. 
Inquiry-to-visit conversion rate 	30%+ 	Measures whether inquiries are actually serious and wellmatched. 
Visit-to-rent conversion rate 	50%+ 	Measures listing accuracy. If people visit and don't rent, the listing is misleading. 
Landlord 30-day retention 	80%+ 	Measures whether landlords keep using the app after joining. 
Waitlist notifications sent 	20+ 	Means houses fill up AND landlords use the waitlist feature. 
 
Secondary Metrics (Useful Context) 
Metric 	What It Tells You 
App opens per active user per week 	Engagement and retention health 
Listings viewed per session 	Discovery effectiveness — are seekers finding relevant options? 
Most common inquiry questions 	What information should be on the listing page but isn't yet 
Average time from inquiry to visit scheduled 	Process efficiency — faster is better 
Tenant announcements read rate 	Whether the tenant layer is actually useful 
 
Vanity Metrics to Ignore 

Do Not Optimize For These 
Total downloads (includes inactive installs), Social media followers or post likes, Number of messages sent (open chat is a feature you don't have — don't build toward it), App store rating (too few reviews to be statistically meaningful at this scale). 
 
11 	Build Plan & Timeline 
 
Recommended Team Structure 
If you are building this as a student project with limited resources: 
•	1 person (you): Product owner, researcher, landlord relationship manager, verifier 
•	1-2 developers: Flutter mobile + Supabase backend 
•	1 designer (can overlap with developer): UI/UX in Figma 
If you are solo: prioritize the backend and admin dashboard first. The mobile app can start as a simple web app (React) that loads in a browser — this reduces Flutter complexity in early phases. 
 
Development Timeline 
Weeks 	Phase 	Deliverables 
1-2 	Phase 0 Research 	10 landlord interviews, 20 seeker interviews, 3 committed landlord partners 
3-4 	Design & Architecture 	Figma prototypes for 6 key screens. 
Database schema finalized. Supabase project set up. 
5-8 	Core Backend 	Auth, listings CRUD, inquiry form, inquiry inbox. Landlord dashboard (web, functional). 
9-12 	Mobile Frontend 	Flutter app: directory, listing detail, inquiry form, visit scheduler, waitlist. 
13-14 	Verification Sprint 	Personally verify 3-5 listings with photos. Test end-to-end flow with real landlords. 
15-16 	Soft Launch 	Invite 20-30 seekers. Monitor and fix critical issues only. No new features. 
17-20 	Phase 1 Stabilization 	Fix bugs, improve onboarding, verify 2-3 more landlords based on feedback. 
21-24 	Phase 2 Build 	Tenant verification, announcement feed, push notifications, inquiry analytics. 
25+ 	Phase 2 Launch + Ongoing 	Tenant layer live. Measure Phase 2 KPIs. Plan Phase 3 only when criteria met. 
 
Budget Considerations 
Item 	Cost Estimate 
Supabase (free tier) 	Free — up to 500MB database, 1GB storage 
Firebase Cloud Messaging 	Free 
Google Maps API (Phase 3 only) 	~$200/year at low usage, or use 
OpenStreetMap free alternative 
Apple Developer Account (iOS) 	$99/year — skip iOS until MVP is validated on 
Android 
Google Play Store 	$25 one-time 
Domain + basic hosting (admin dashboard) 	~$10-20/year 
Printing (tarpaulins, QR flyers) 	~₱500-1000 per semester 
Total MVP Launch Cost 	~₱3,000-5,000 + your time 
 
12 	The Honest Final Word 
 
What This App Can Realistically Become 
Within 12 months of a successful launch, Buhay Boarding can be the default tool for finding a boarding house in Burauen. Not one of the tools — the tool. In a market this specific and this underserved, owning the category entirely is achievable. That is a more valuable outcome than a mediocre app in a bigger market. 
 
The Three Ways This Fails 
1. You build before you research 
If you write code before talking to 8 landlords, you will build the wrong thing. The most common cause of student project failure is building what sounds good instead of building what people actually need. The research phase is not optional. 
2. You launch with one landlord 
One anchor is fragile. If they get busy, lose interest, or feel the app is not useful, your entire listing supply disappears. You need three minimum, and they must be genuinely committed — not politely agreeable. 
3. You add features faster than you gain users 
Every unneeded feature is a bug that hasn't happened yet. The discipline to stop adding things is harder than the skill to build them. Set a rule: no new features until the last one is being actively used by at least 10 real people. 
 
The Three Ways This Succeeds 
1. Landlords love it 
If even two landlords tell their landlord friends 'this saves me time,' the platform grows without marketing. This is your best-case growth engine. 
2. You are present at enrollment season 
The highest-leverage moment for a boarding house app is the week before a new semester when hundreds of students are simultaneously looking for rooms. Be there, be visible, and be the only verified option. 
3. You treat every early user like they matter 
In the first 3 months, personally message every new user. Ask them what was confusing. Ask them what they wished the app did. Do this yourself — not through a form, not through analytics. A personal message. These conversations will shape the product more than any planning document, including this one. 
 
 
 
 
Final Reminder 
This masterplan is a starting point, not a contract. Reality will change it. A landlord will suggest something you haven't thought of. A seeker will use a feature in a way you didn't design for. A competitor might appear. Stay anchored to the core problem — reducing friction in finding a boarding house in Burauen — and every adaptation will make sense. Everything else is negotiable. 
 
 
Build it. Earn its existence. 
