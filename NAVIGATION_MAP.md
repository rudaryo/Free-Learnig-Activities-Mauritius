# 🗺️ NAVIGATION FLOW MAP

## Visual Guide to Your Website Structure

```
┌─────────────────────────────────────────────────────────────┐
│                                                               │
│                    INDEX.HTML (MAIN PAGE)                     │
│                 🎓 Interactive Learning Platform              │
│                                                               │
│   ┌──────────┬──────────┬──────────┬──────────┬──────────┐  │
│   │ Grade 1  │ Grade 2  │ Grade 3  │ Grade 4  │ Grade 5  │  │
│   │    ✅    │    🚧    │    🚧    │    🚧    │    ✅    │  │
│   └──────────┴──────────┴──────────┴──────────┴──────────┘  │
│                                                               │
└──────────┬──────────────────────────────────────┬────────────┘
           │                                      │
           ▼                                      ▼
┌──────────────────────────┐        ┌──────────────────────────┐
│   GRADE 1 INDEX          │        │   GRADE 5 INDEX          │
│   grade-1-index.html     │        │   grade-5-index.html     │
│                          │        │                          │
│  ┌─────────────────────┐ │        │  ┌─────────────────────┐ │
│  │ 📊 Mathematics ✅   │ │        │  │ 🔢 Mathematics 🚧  │ │
│  │ 22+ Activities      │ │        │  │                     │ │
│  └─────────────────────┘ │        │  └─────────────────────┘ │
│                          │        │                          │
│  ┌─────────────────────┐ │        │  ┌─────────────────────┐ │
│  │ 📚 English 🚧       │ │        │  │ 🗺️ His-Geo ✅      │ │
│  │ Coming Soon         │ │        │  │ 15 Topics           │ │
│  └─────────────────────┘ │        │  └─────────────────────┘ │
│                          │        │                          │
│  ┌─────────────────────┐ │        │  ┌─────────────────────┐ │
│  │ 🇫🇷 French 🚧        │ │        │  │ 🔬 Science 🚧      │ │
│  │ Coming Soon         │ │        │  │ Coming Soon         │ │
│  └─────────────────────┘ │        │  └─────────────────────┘ │
└──────────┬───────────────┘        └──────────┬───────────────┘
           │                                   │
           ▼                                   ▼
┌──────────────────────────┐        ┌──────────────────────────┐
│ MATH TOPICS MENU         │        │ HIS-GEO TOPICS MENU      │
│ grade-1-math-index.html  │        │ grade-5-his-geo-index... │
│                          │        │                          │
│ ┌──────────────────────┐ │        │ ┌──────────────────────┐ │
│ │ 🔢 NUMBERS          │ │        │ │ 🌋 Volcanoes ✅     │ │
│ │ • Recognition       │ │        │ │ • Label Volcano     │ │
│ │ • Counting          │ │        │ │                     │ │
│ │ • Writing           │ │        │ └──────────────────────┘ │
│ │ • Ordering          │ │        │                          │
│ │ • Addition          │ │        │ ┌──────────────────────┐ │
│ │ • Ordinals          │ │        │ │ ⛰️ Relief Features  │ │
│ │ 22+ Activities      │ │        │ │ Coming Soon         │ │
│ └──────────────────────┘ │        │ └──────────────────────┘ │
│                          │        │                          │
│ ┌──────────────────────┐ │        │ ┌──────────────────────┐ │
│ │ ⭐ SHAPES           │ │        │ │ 🇳🇱 Dutch Period    │ │
│ │ • Identification    │ │        │ │ Coming Soon         │ │
│ │ • Learning          │ │        │ └──────────────────────┘ │
│ │ 1+ Activities       │ │        │                          │
│ └──────────────────────┘ │        │ ... 12 more topics 🚧   │
│                          │        │                          │
│ 🚧 Coming Soon:          │        └──────────┬───────────────┘
│ • Colours                │                   │
│ • Length                 │                   ▼
│ • Time                   │        ┌──────────────────────────┐
│ • Measure                │        │ VOLCANO ACTIVITY         │
└──────────┬───────────────┘        │ volcano_parts_activity.. │
           │                        │                          │
           ▼                        │ 🌋 Interactive Diagram   │
┌──────────────────────────┐        │ • Drag & Drop Labels    │
│ INDIVIDUAL ACTIVITIES    │        │ • 7 Volcano Parts       │
│ (22 Number Activities)   │        │ • Requires volcano.png  │
│                          │        │                          │
│ • Recognising Numerals   │        │ [Back] button →         │
│ • Learn to Count         │        │   His-Geo Index         │
│ • Counting Up to 10 ✨   │        └─────────────────────────┘
│ • Ten Frames             │
│ • Ordinal Numbers 🏁     │
│ • Addition Activities ➕ │
│ • ... and more!          │
│                          │
│ [Back] button →          │
│   Math Topics Menu       │
└──────────────────────────┘
```

## 🔄 BACK BUTTON NAVIGATION

### From Activities
```
Activity → [Back] → Subject Topics Menu
Example: counting-up-to-10.html → grade-1-math-index.html
```

### From Subject Topics Menu
```
Subject Topics → [Back] → Grade Subjects Menu
Example: grade-1-math-index.html → grade-1-index.html
```

### From Grade Subjects Menu
```
Grade Subjects → [Back] → Main Page
Example: grade-1-index.html → index.html
```

## 📂 FILE LOCATIONS

### Grade 1 Math Activities
```
Grade-1/
  └── Mathematics/
      ├── grade-1-math-index.html    ← Topics menu
      ├── Numbers/
      │   ├── activity1.html          ← Your 22 activities here
      │   ├── activity2.html
      │   └── ...
      ├── Shapes/
      │   └── learning-shapes.html    ← Shape activity here
      └── assets/
          ├── images/                 ← Future math images
          ├── audio/                  ← Future math sounds
          └── css/                    ← Future math styles
```

### Grade 5 His-Geo Activities
```
Grade-5/
  └── History-Geography/
      ├── grade-5-his-geo-index.html  ← Topics menu
      ├── history and geography/
      │   └── volcano_parts_activity.html
      └── assets/
          ├── images/
          │   └── volcano.png         ← REQUIRED IMAGE!
          ├── audio/
          └── css/
```

## 🎯 USER JOURNEY EXAMPLES

### Example 1: Student Accessing Math Activity
```
1. Open: learning-for-fun.org (index.html)
2. Click: "Grade 1" card
3. Click: "Mathematics" card
4. Scroll to: "Numbers Activities" section
5. Click: "Counting Up to 10" activity
6. Complete activity
7. Click: Back button → Returns to Math Topics Menu
8. Click: Back button → Returns to Grade 1 Subjects
9. Click: Back button → Returns to Main Page
```

### Example 2: Student Accessing Volcano Activity
```
1. Open: learning-for-fun.org (index.html)
2. Click: "Grade 5" card
3. Click: "History & Geography" card
4. Scroll to: "Volcanoes in our Region" section
5. Click: "Label the Volcano" activity
6. Complete labeling exercise
7. Click: Back button → Returns to His-Geo Topics Menu
8. Click: Back button → Returns to Grade 5 Subjects
9. Click: Back button → Returns to Main Page
```

## 📱 RESPONSIVE DESIGN

### Desktop View
```
┌─────────────────────────────────────┐
│  [Grade 1] [Grade 2] [Grade 3]      │
│  [Grade 4] [Grade 5] [Grade 6]      │  ← Grid layout
└─────────────────────────────────────┘
```

### Tablet View
```
┌──────────────────────────┐
│  [Grade 1] [Grade 2]     │
│  [Grade 3] [Grade 4]     │  ← 2-column grid
│  [Grade 5] [Grade 6]     │
└──────────────────────────┘
```

### Mobile View
```
┌──────────────┐
│  [Grade 1]   │
│  [Grade 2]   │
│  [Grade 3]   │  ← Single column
│  [Grade 4]   │
│  [Grade 5]   │
│  [Grade 6]   │
└──────────────┘
```

## 🎨 COLOR CODING

- **Green** 🟢 = Mathematics
- **Gray** ⚪ = English  
- **Yellow** 🟡 = French
- **Pink** 🔴 = History & Geography
- **Purple** 🟣 = Science
- **Light Purple** 🟣 = Social Sciences

## ✅ STATUS LEGEND

- ✅ = Available (clickable, has content)
- 🚧 = Coming Soon (placeholder, not clickable)
- ✨ = New Activity (has "NEW!" badge)

## 🗂️ CONTENT SUMMARY

### Currently Available:
- **Grade 1 Mathematics**: 22+ activities across Numbers and Shapes
- **Grade 5 His-Geo**: 1 activity (Volcanoes), 14 topics planned

### Coming Soon:
- Grade 1: English, French
- Grade 2-4: All subjects
- Grade 5: Mathematics, English, French, Science
- Grade 6: All subjects

---

**This map shows the complete navigation structure of your learning platform! 🗺️**
