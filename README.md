# Learning For Fun - Interactive Educational Platform

## 🎓 Overview
Welcome to the **Learning For Fun** interactive educational platform developed by Ramsamy Rudaryo. This platform provides engaging, interactive learning activities for primary school pupils (Grades 1-6).

## 📚 Current Content

### Grade 1
- **Mathematics** ✅ (22+ activities available)
  - Numbers (counting, recognition, writing, ordering, addition)
  - Shapes (identification, learning)
  - Coming soon: Colours, Length, Time, Measure

### Grade 5
- **History & Geography** ✅ (15 topics, 1 activity available)
  - Geography: Volcanoes, Relief Features, Environment, Temperature, Rainfall
  - History: Indian Ocean, Mascarene Islands, Dutch Settlement, French Period, British Colony

### Other Grades
- Grades 2, 3, 4, and 6 content is currently under development

## 🗂️ Repository Structure

```
learning-for-fun/
├── index.html                          # Main landing page (all grades)
│
├── Grade-1/
│   ├── grade-1-index.html             # Grade 1 subject selector
│   └── Mathematics/
│       ├── grade-1-math-index.html    # Math topics menu
│       ├── assets/                     # Math resources (for future use)
│       │   ├── images/
│       │   ├── audio/
│       │   └── css/
│       ├── Numbers/                    # Number activities folder
│       └── Shapes/                     # Shape activities folder
│
├── Grade-2/ through Grade-4/          # Placeholders (coming soon)
│
├── Grade-5/
│   ├── grade-5-index.html             # Grade 5 subject selector
│   └── History-Geography/
│       ├── grade-5-his-geo-index.html # His-Geo topics menu
│       ├── assets/                     # His-Geo resources
│       │   └── images/
│       │       └── volcano.png         # Volcano diagram image
│       └── history and geography/      # Activity files
│           └── volcano_parts_activity.html
│
└── Grade-6/                            # Placeholder (coming soon)
```

## 🚀 Getting Started

### For Developers

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/learning-for-fun.git
   cd learning-for-fun
   ```

2. **Add your activity files:**
   - Place math activities in: `Grade-1/Mathematics/Numbers/` or `Grade-1/Mathematics/Shapes/`
   - Place assets in the appropriate `assets/` folder within each subject
   - Update the subject index file to include new activities

3. **Test locally:**
   - Open `index.html` in a web browser
   - Navigate through grades → subjects → activities
   - Test all navigation (back buttons, activity links)

4. **Deploy to GitHub Pages:**
   - Push changes to your repository
   - Enable GitHub Pages in repository settings
   - Your site will be available at: `https://yourusername.github.io/learning-for-fun/`

### File Path Guidelines

All file paths are **relative** to maintain compatibility with GitHub Pages:

- **From index.html**: `Grade-1/grade-1-index.html`
- **From grade-1-index.html**: `Mathematics/grade-1-math-index.html`
- **From math activities**: `../assets/images/picture.png`
- **Back buttons**: `../grade-1-index.html` or `../index.html`

## 📝 Adding New Content

### Adding Activities to Existing Subjects

1. Create your HTML activity file
2. Place it in the appropriate folder (e.g., `Grade-1/Mathematics/Numbers/`)
3. Add required images/audio to the `assets/` folder
4. Update the subject index file's JavaScript array:

```javascript
const numbersFiles = [
    {file:"your-new-activity.html", icon:"🎯", level:"Activity Description", title:"Activity Title", badge:"NEW!"}
];
```

### Adding New Subjects

1. Create subject folder: `Grade-X/SubjectName/`
2. Create `assets/` subfolder with `images/`, `audio/`, and `css/`
3. Create subject index file: `grade-X-subjectname-index.html`
4. Update the grade index file to link to your new subject

### Adding New Grades

1. Create grade folder: `Grade-X/`
2. Create grade index: `grade-X-index.html`
3. Update main `index.html` to include the new grade
4. Create subject folders as needed

## 🎨 Design Guidelines

- Use responsive design (mobile-first approach)
- Follow existing color scheme and styles
- Include clear back navigation
- Use emojis for visual appeal
- Ensure accessibility (large buttons, clear fonts)
- Test on Android tablets (Samsung devices used in schools)

## 🔧 Technical Notes

### Math Activities
- Use emojis for visual elements
- Implement text-to-speech for audio feedback
- No external asset files required for most activities
- Optimized for offline use

### History & Geography Activities
- Store images in `assets/images/`
- Use relative paths: `../assets/images/filename.png`
- Include drag-and-drop functionality where appropriate

## 📱 Device Compatibility

This platform is designed to work on:
- Desktop computers
- Android tablets (Samsung Galaxy Tab)
- Mobile phones
- Various screen sizes and orientations

## 👥 Contributing

When contributing new activities:

1. Follow the existing folder structure
2. Use consistent naming conventions
3. Test on multiple devices
4. Ensure all links and paths are relative
5. Include appropriate back navigation
6. Add activity to the relevant index file

## 📄 License

© 2024 Service Diocésain de l'Éducation Catholique (SeDEC) - Mauritius

## 📧 Contact

For questions or contributions, please contact:
- **Organization**: SeDEC (Service Diocésain de l'Éducation Catholique)
- **Website**: learning-for-fun.org
- **Coverage**: 46 Roman Catholic Authority Schools in Mauritius

## 🎯 Future Plans

- Complete all Grade 1 topics (Colours, Length, Time, Measure)
- Develop English and French content for Grade 1
- Create activities for Grades 2-6
- Add more History & Geography activities for Grade 5
- Implement progress tracking
- Add teacher dashboard

---

**Happy Learning! 📚✨**
