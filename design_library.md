# Design Library

## Project
A multimodal mood-tracking app using:
- short video check-ins
- smartwatch biometric data
- conversational guidance
- AI analysis
- transcript-based review

## Main problem
Current mood trackers usually require manual end-of-day input.
Main limits:
- high effort
- poor recall
- one entry per day is too reductive
- charts often do not help interpretation

## Relevant benchmark categories
### 1. Mood-tracking apps
Useful for:
- quick logging
- calendars
- charts
Limits:
- too manual
- too simple

### 2. Journaling apps
Useful for:
- richer reflection
- notes and context
Limits:
- too much effort
- hard to use in bad moments

### 3. Video / voice diary tools
Useful for:
- richer emotional capture
- tone and facial expression
Limits:
- privacy concerns
- hard to revisit negative moments

### 4. Wearables / smartwatch tools
Useful for:
- passive data
- heart rate / sleep / stress context
Limits:
- trust and privacy issues
- biometrics are not emotion by themselves

### 5. AI / conversational wellbeing tools
Useful for:
- guided self-expression
- summaries
- pattern detection
Limits:
- may feel invasive
- needs explainability

## Key design opportunities
- reduce manual input
- capture multiple moments per day
- combine video + biometrics
- provide transcript instead of forcing video replay
- give simple summaries, not only charts
- keep privacy and user control central

## Design directions
### A. Guided video check-in
Short guided videos during the day.

### B. Hybrid mood dashboard
Video + smartwatch data shown together.

### C. Safe reflection system
Transcript-first review, summaries, and optional AI insights.

## Main takeaways
The prototype should:
- avoid only manual end-of-day logging
- use multimodal input
- support low effort
- provide safer review of negative moments
- make AI suggestions optional and understandable
