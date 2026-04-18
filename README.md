# Graphestra — Measure Difficulty Graph

A simple web-based practice chart tool for music teachers and students. Quickly rate the difficulty of each measure in a piece, and generate a printable graph that tracks practice progress.

## How to Use

### 1. Open the App
Open `index.html` in any modern web browser on your iPad, computer, or phone. Safari on iPad works great.

### 2. Enter Piece Details
- **Measures in the piece**: Enter the total number of measures (1–200)
- **Song name**: Optional, but appears as the title on printed pages
- **Student name**: Optional, appears as the subtitle on printed pages

### 3. Rate Each Measure
- The app shows "Measure X of N"
- For each measure, tap a difficulty rating from **1** (easy) to **10** (hard)
- The graph updates live as you rate
- Use **Previous/Next** buttons or tap any column on the graph to jump to that measure
- Keyboard shortcuts: arrow keys to navigate, 1–9 or 0 (for 10) to rate

### 4. Understand the Graph
- **Y-axis**: 1–10 difficulty scale (plus 2 bonus rows above for extra practice)
- **X-axis**: Measure numbers
- **Red dash**: Shows the difficulty level for that measure
- **Red line**: Connects adjacent measures (gaps stay broken)
- **Grid cells**: Students will fill one cell per practice session, from bottom up to the dash

### 5. Print the Chart
- Click the **Print…** button
- A preview modal shows what will print (landscape page layout)
- Review and click **Print** in the modal
- Your browser's print dialog opens — adjust settings and print to PDF or paper
- Each page shows the song name, student name, and measures for that section
- Pages are automatically split if the piece is long (32 measures per page)

### 6. Student Practice
Print the chart and give it to your student. They fill in cells from the bottom up:
- For a measure rated difficulty **1**: fill the 1st cell
- For difficulty **10**: fill all 10 cells
- Each time they practice, they add a cell for that measure
- They can keep practicing beyond the difficulty level if they want extra work

### 7. Start Over
Click **New Graph** to clear all ratings and start fresh. You'll be asked to confirm.

## Features

✓ **Live updates** — graph changes as you rate each measure  
✓ **Flexible navigation** — jump between measures easily  
✓ **Responsive design** — works on iPad, tablets, and desktop  
✓ **Multi-page printing** — splits long pieces automatically  
✓ **Auto-save** — your data is saved in browser storage (survives page reloads)  
✓ **Clean graph paper** — aligned grid with clear difficulty levels  
✓ **No accounts needed** — entirely local, no sign-up or data sharing  

## Tips

- **On iPad**: Use in landscape for the widest view; scroll with the arrow buttons if needed
- **Keyboard**: Use arrow keys + number keys for fastest rating (no mouse needed)
- **Measure counts**: You can change the measure count any time; it drops ratings for measures beyond the new count
- **Long pieces**: The app automatically creates multiple print pages; each page includes the song/student names
- **Difficulty mapping**: 
  - 1–3 = easy (little practice needed)
  - 4–6 = moderate (some focus)
  - 7–10 = challenging (lots of repetition)

## Browser Support

Works in:
- **iPad Safari** (recommended)
- **Chrome/Edge** (desktop and mobile)
- **Firefox** (desktop and mobile)
- Any modern browser with JavaScript enabled

## Privacy

All data is stored locally in your browser. Nothing is sent to any server — the entire app runs on your device.

---

**Questions or feedback?** This tool was built to make practice tracking simple and visual for music students of all ages.
