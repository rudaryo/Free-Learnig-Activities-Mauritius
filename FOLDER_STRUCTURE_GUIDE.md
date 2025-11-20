# FOLDER STRUCTURE GUIDE

## 📁 Complete Directory Structure

```
learning-for-fun/
│
├── index.html                                    # ✅ MAIN ENTRY POINT
├── README.md                                     # ✅ Documentation
│
├── Grade-1/
│   ├── grade-1-index.html                       # ✅ Grade 1 subjects page
│   │
│   ├── Mathematics/
│   │   ├── grade-1-math-index.html              # ✅ Math topics menu
│   │   ├── assets/
│   │   │   ├── images/                          # 📁 Place math images here
│   │   │   ├── audio/                           # 📁 Place math audio files here
│   │   │   └── css/                             # 📁 Place math stylesheets here
│   │   ├── Numbers/
│   │   │   ├── Recognising_numerals_1_to_8.html
│   │   │   ├── learn_to_count.html
│   │   │   ├── counting-up-to-10.html
│   │   │   └── ... (all 22+ number activities)  # ⬆️ PLACE NUMBER ACTIVITIES HERE
│   │   └── Shapes/
│   │       └── learning-shapes.html              # ⬆️ PLACE SHAPE ACTIVITIES HERE
│   │
│   ├── English/
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── audio/
│   │   │   └── css/
│   │   └── (coming soon - future activities here)
│   │
│   └── French/
│       ├── assets/
│       │   ├── images/
│       │   ├── audio/
│       │   └── css/
│       └── (coming soon - future activities here)
│
├── Grade-2/
│   ├── grade-2-index.html                       # ✅ Placeholder page
│   ├── Mathematics/
│   │   └── assets/
│   ├── English/
│   │   └── assets/
│   └── French/
│       └── assets/
│
├── Grade-3/
│   ├── grade-3-index.html                       # ✅ Placeholder page
│   ├── Mathematics/
│   │   └── assets/
│   ├── English/
│   │   └── assets/
│   ├── French/
│   │   └── assets/
│   └── Social-Sciences/
│       └── assets/
│
├── Grade-4/
│   ├── grade-4-index.html                       # ✅ Placeholder page
│   ├── Mathematics/
│   │   └── assets/
│   ├── English/
│   │   └── assets/
│   ├── French/
│   │   └── assets/
│   ├── History-Geography/
│   │   └── assets/
│   └── Science/
│       └── assets/
│
├── Grade-5/
│   ├── grade-5-index.html                       # ✅ Grade 5 subjects page
│   │
│   ├── Mathematics/
│   │   └── assets/
│   │       ├── images/
│   │       ├── audio/
│   │       └── css/
│   │
│   ├── English/
│   │   └── assets/
│   │       ├── images/
│   │       ├── audio/
│   │       └── css/
│   │
│   ├── French/
│   │   └── assets/
│   │       ├── images/
│   │       ├── audio/
│   │       └── css/
│   │
│   ├── History-Geography/
│   │   ├── grade-5-his-geo-index.html           # ✅ His-Geo topics menu
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   │   └── volcano.png                  # ✅ Volcano image HERE
│   │   │   ├── audio/
│   │   │   └── css/
│   │   └── history and geography/
│   │       └── volcano_parts_activity.html      # ✅ Volcano activity
│   │       └── (future activities here)         # ⬆️ PLACE HIS-GEO ACTIVITIES HERE
│   │
│   └── Science/
│       └── assets/
│           ├── images/
│           ├── audio/
│           └── css/
│
└── Grade-6/
    ├── grade-6-index.html                       # ✅ Placeholder page
    ├── Mathematics/
    │   └── assets/
    ├── English/
    │   └── assets/
    ├── French/
    │   └── assets/
    ├── History-Geography/
    │   └── assets/
    └── Science/
        └── assets/
```

## 📍 WHERE TO PLACE YOUR FILES

### Math Activities (Grade 1)

**Your 22 Number Activities go here:**
```
Grade-1/Mathematics/Numbers/
├── Recognising_numerals_1_to_8.html
├── Recognise_numerals_1_to_10.html
├── listen_and_read_1_to_10.html
├── number_listening_activities.html
├── learn_to_count_1_to_8.html
├── learn_to_count.html
├── counting-shapes-game.html
├── counting-up-to-10.html
├── ten-frames-assessment.html
├── learning_zero.html
├── trace_numerals.html
├── Pick-Number-Name.html
├── match_numeral_to_name.html
├── write_missing_letter.html
├── number-learning-game.html
├── put-numbers-in-order.html
├── what-comes-next.html
├── i-put-together.html
├── drag-drop-addition.html
├── make-it-ten.html
├── write-addition-sentence.html
├── ordinal-numbers-game.html
├── ordinal-numbers-race-game.html
└── complete-ordinal-sequence.html
```

**Shape Activities go here:**
```
Grade-1/Mathematics/Shapes/
└── learning-shapes.html
```

**Math Assets (if needed):**
```
Grade-1/Mathematics/assets/
├── images/          ← Math-related images
├── audio/           ← Math-related sounds
└── css/             ← Math-specific stylesheets
```

### History & Geography Activities (Grade 5)

**Current Activity:**
```
Grade-5/History-Geography/history and geography/
└── volcano_parts_activity.html  ✅ Already placed
```

**Volcano Image:**
```
Grade-5/History-Geography/assets/images/
└── volcano.png  ⚠️ YOU NEED TO UPLOAD THIS IMAGE
```

**Future His-Geo Activities:**
Place them in: `Grade-5/History-Geography/history and geography/`

**Future His-Geo Assets:**
```
Grade-5/History-Geography/assets/
├── images/          ← Geography maps, historical images
├── audio/           ← Historical narrations, pronunciations
└── css/             ← His-Geo specific styles
```

## 🔗 FILE PATH REFERENCES

### From Activity Files to Assets

**Grade 1 Math activity** (`Grade-1/Mathematics/Numbers/activity.html`):
```html
<img src="../assets/images/picture.png">
<audio src="../assets/audio/sound.mp3">
```

**Grade 5 His-Geo activity** (`Grade-5/History-Geography/history and geography/activity.html`):
```html
<img src="../assets/images/volcano.png">
```

### Navigation Back Buttons

**From Math activity** to math index:
```html
<button onclick="window.location.href='../grade-1-math-index.html'">
```

**From Math index** to grade index:
```html
<button onclick="window.location.href='../grade-1-index.html'">
```

**From Grade index** to main:
```html
<button onclick="window.location.href='../index.html'">
```

## ✅ CHECKLIST FOR UPLOADING TO GITHUB

### Files Already Created:
- ✅ `index.html` (main page)
- ✅ `Grade-1/grade-1-index.html`
- ✅ `Grade-1/Mathematics/grade-1-math-index.html`
- ✅ `Grade-2/grade-2-index.html` (placeholder)
- ✅ `Grade-3/grade-3-index.html` (placeholder)
- ✅ `Grade-4/grade-4-index.html` (placeholder)
- ✅ `Grade-5/grade-5-index.html`
- ✅ `Grade-5/History-Geography/grade-5-his-geo-index.html`
- ✅ `Grade-5/History-Geography/history and geography/volcano_parts_activity.html`
- ✅ `Grade-6/grade-6-index.html` (placeholder)
- ✅ `README.md`

### Files YOU Need to Upload:

**Math Activities (22 files):**
```
📂 Upload to: Grade-1/Mathematics/Numbers/
   - Recognising_numerals_1_to_8.html
   - Recognise_numerals_1_to_10.html
   - listen_and_read_1_to_10.html
   - ... (all other number activities)
```

**Shape Activities:**
```
📂 Upload to: Grade-1/Mathematics/Shapes/
   - learning-shapes.html
```

**Volcano Image:**
```
📂 Upload to: Grade-5/History-Geography/assets/images/
   - volcano.png  ⚠️ CRITICAL - Activity won't work without this!
```

### Empty Folders to Create:

GitHub doesn't track empty folders, so you'll need to add `.gitkeep` files or just create them as you add content:

```
Grade-1/Mathematics/assets/images/
Grade-1/Mathematics/assets/audio/
Grade-1/Mathematics/assets/css/
Grade-1/English/assets/
Grade-1/French/assets/
(and similar for other grades...)
```

## 🚀 DEPLOYMENT STEPS

1. **Initialize Git repository:**
   ```bash
   cd learning-for-fun
   git init
   git add .
   git commit -m "Initial commit - Learning platform structure"
   ```

2. **Create GitHub repository:**
   - Go to GitHub.com
   - Create new repository: "learning-for-fun"
   - Don't initialize with README (you already have one)

3. **Push to GitHub:**
   ```bash
   git remote add origin https://github.com/YOUR-USERNAME/learning-for-fun.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to repository Settings
   - Pages section
   - Source: Deploy from main branch
   - Root directory: / (root)
   - Save

5. **Your site will be live at:**
   ```
   https://YOUR-USERNAME.github.io/learning-for-fun/
   ```

## 📝 NOTES

- All paths are **relative** - they work locally and on GitHub Pages
- The `history and geography` folder name has spaces (from your original structure)
- Asset folders are ready for future resources
- Math activities use emojis/text-to-speech (no external assets needed currently)
- Volcano activity REQUIRES `volcano.png` in the assets folder to work

---

**Questions? Check README.md for more details!**
