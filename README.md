# Daily Tracker V1.1

A simple, single-page web app for tracking daily activities, behaviors, mood, and health metrics. Perfect for monitoring patterns and documenting daily progress.

## Features

### Today Tab
Quick daily check-in with comprehensive tracking:
- **Date Selection** — Choose the date for your entry
- **School** — Attended, stayed home, or not scheduled (with optional reason)
- **Mood** — Multi-select from 11 emotions (happy, calm, anxious, tired, etc.)
- **Behavior** — Track meltdowns with detailed logging:
  - Duration (under 5 min to 60+ min)
  - Violence/aggression
  - Trigger identification
  - What helped
  - Notes
- **Bathroom** — Track bowel movements and frequency
- **Eating** — Log meals (breakfast, lunch, dinner, snacks) and overall eating quality
- **Sleep** — Previous night's sleep time, wake-ups, and quality rating (1-5 stars)
- **Medications** — Track Melatonin and Fluoxetine dosage and timing
- **Notes** — Free-form notes for anything else worth remembering

### Dashboard Tab
Monthly statistics and patterns:
- Good sleep percentage
- Eating well percentage
- School attendance rate
- Bowel movement tracking
- Meltdown days percentage
- Total wake-ups
- **Meltdown Patterns** — Shows top 5 triggers and most effective responses

### History Tab
View all saved entries with:
- Date-formatted display
- Quick summary (school, mood, meltdowns, eating, sleep)
- Edit button to reload any past entry

## How to Use

1. **Open** `index.html` in any web browser
2. **Fill out today's entry** using the form on the "Today" tab
3. **Save** — Changes auto-save as you type, or click "Save today's entry"
4. **View patterns** — Go to "Dashboard" to see monthly statistics
5. **Review history** — Check "History" to view or edit past days

## Data Storage

- All data is stored locally in your browser (localStorage)
- No server or internet connection required
- Data persists until you clear your browser's local storage
- Melatonin dose is remembered for future entries

## Customization

Edit `index.html` to customize:
- Color scheme (CSS variables in `:root`)
- Mood options
- Meltdown duration/trigger/response options
- Medication names and tracking fields

## Technical Details

- Pure HTML, CSS, and JavaScript — no dependencies
- Single-file application
- Responsive design for desktop and mobile
- Auto-save functionality (300ms debounce)
- JSON data format for easy export/backup

## Tips

- Use the "Add meltdown details" button to log specifics about behavioral incidents
- The dashboard automatically calculates percentages based on the current month
- Edit past entries anytime by clicking the "Edit" button in History
- Your medication dose is saved and pre-filled on future days

---

Created for daily tracking and pattern identification.
