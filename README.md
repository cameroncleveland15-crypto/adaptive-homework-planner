# Adaptive Homework Planner for Students

## Product Vision
Build a smart homework planner that automatically adapts to a student’s real school schedule, workload, and deadlines. The app should reduce stress, prevent last-minute cramming, and help students complete assignments on time by intelligently planning when homework should be done.

Target users: **Middle school, high school, and college students**

Platforms: **Web app (mobile-first), optional PWA**

---

## Core Problems This App Solves
1. Students forget assignments
2. Students underestimate how long homework takes
3. Schedules change (rotating days, block schedules)
4. Students procrastinate until deadlines
5. Poor time management after school

---

## Core Features (Must-Have)

### 1. User Accounts & Profiles
- Email + password authentication
- OAuth (Google / Apple)
- User profile fields:
  - Name
  - School name
  - Grade level
  - Timezone
  - Preferred study hours
  - Weekend study preference (on/off)
  - Typical homework difficulty (easy/medium/hard)

---

### 2. School Schedule Engine (Critical Feature)
Support **multiple schedule types**:

#### Schedule Types
- Standard (same classes daily)
- Block schedule (A/B days)
- Rotating cycle (Day 1–6)
- College-style weekly schedule
- Custom schedule builder

#### Schedule Data Model
- Class name
- Teacher
- Room (optional)
- Start time
- End time
- Day(s) active
- Rotation label (A/B/C/etc.)

#### Behavior
- Automatically detects what classes occur **today**
- Adjusts homework availability based on:
  - School hours
  - Free periods
  - After-school time
- Handles:
  - Holidays
  - Half-days
  - No-school days
  - Exam days

---

## [Other Sections...]
