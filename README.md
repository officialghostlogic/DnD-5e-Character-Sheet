# D&D 5e Character Dashboard

A modern, interactive web-based character sheet for Dungeons & Dragons 5th Edition. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and ease of use.

![Character Dashboard Preview](https://via.placeholder.com/800x400/6b4423/f4f1e8?text=D%26D+5e+Character+Dashboard)

## ✨ Features

### 🎲 Interactive Dice Rolling
- **One-click dice rolls** for ability checks, skills, saves, and combat
- **Visual roll results** with critical hit/fumble detection
- **Roll history tracker** with floating widget
- **Animated roll popups** with customizable settings

### 📊 Complete Character Management
- **Vital Statistics**: HP tracking with visual bar, AC, speed
- **Ability Scores**: All six abilities with modifier calculation
- **Combat Tracking**: Initiative, proficiency, hit dice, death saves
- **Skills & Saves**: Proficiency tracking with auto-calculated bonuses
- **Spellcasting**: Spell slots, known spells, concentration tracking
- **Equipment**: Inventory management with currency tracking
- **Conditions**: Status effect tracking with common D&D conditions
- **Notes**: Session notes, character backstory, plot reminders

### 🎨 Modern Design
- **Glassmorphism UI** with elegant transparency effects
- **Fantasy Theming** with custom fonts (Cinzel & Crimson Text)
- **Responsive Layout** that works on desktop, tablet, and mobile
- **Dark/Light Themes** with smooth transitions
- **Hover Effects** and smooth animations throughout

### ♿ Accessibility Features
- **Font Size Controls** (Small, Normal, Large, Extra Large)
- **High Contrast Mode** for improved visibility
- **Reduced Motion** option for sensitive users
- **Enhanced Keyboard Navigation** with tab support
- **Mobile-Friendly Mode** with larger touch targets
- **Screen Reader Compatible** with proper ARIA labels

### 💾 Data Management
- **Auto-Save** functionality (configurable)
- **Export to Text** with beautifully formatted character sheets
- **Template Loading** for quick character creation
- **Local Storage** for session persistence

## 🚀 Getting Started

### Installation
1. **Download** the HTML file
2. **Open** in any modern web browser
3. **Start playing!** No server or installation required

### Basic Usage
1. **Edit Sections**: Click any card to edit that section
2. **Roll Dice**: Hover over stats to reveal dice buttons, or click to roll
3. **Track Resources**: Use hit dice, death saves, and condition tracking
4. **Take Notes**: Keep session and character notes organized
5. **Export**: Save your character sheet as a formatted text file

## 🎯 Core Sections

### ⚡ Vital Stats
- Current/Max HP with visual health bar
- Armor Class and Speed tracking
- Color-coded health status (green/yellow/red)

### 💪 Ability Scores
- All six D&D abilities (STR, DEX, CON, INT, WIS, CHA)
- Automatic modifier calculation
- One-click ability check rolling

### ⚔️ Combat
- Initiative tracking with DEX modifier
- Proficiency bonus calculation
- Hit dice management with healing rolls
- Death saving throws with success/failure tracking
- Saving throw proficiencies

### 🎯 Skills & Saves
- Skill proficiency tracking
- Automatic bonus calculation
- Quick skill check rolling
- Saving throw proficiency management

### ✨ Spells & Magic
- Spellcasting ability selection
- Spell slot tracking by level
- Known spells list
- Concentration tracking with save rolling

### 🎒 Equipment
- Item inventory with quantity, weight, and notes
- Currency tracking (CP, SP, GP, PP)
- Equipment notes for stats and special properties

### 🔥 Conditions & Status
- Inspiration tracking
- Concentration management
- Common D&D conditions (Blinded, Charmed, etc.)
- Quick condition toggle interface

### 📝 Notes & Reminders
- Session notes for what happened
- Character notes for backstory and personality
- Plot reminders for important NPCs and threads

## ⚙️ Settings & Customization

### 🎨 Visual Settings
- **Font Size**: 4 size options from small to extra-large
- **High Contrast**: Black/white mode for visibility
- **Reduced Motion**: Disables animations for accessibility

### 🎲 Dice Settings
- **Roll Sounds**: Audio feedback for dice rolls
- **Auto-roll Hover**: Show/hide dice buttons on hover
- **Roll Confirmation**: Confirm before rolling dice

### 🖱️ Interaction Settings
- **Click Feedback**: Visual button press feedback
- **Keyboard Navigation**: Enhanced tab navigation
- **Tooltip Delays**: Customizable hover delays

### 📱 Mobile Settings
- **Mobile-Friendly Mode**: Larger touch targets
- **Swipe Navigation**: Gesture support (coming soon)

### 💾 Data Settings
- **Auto-Save**: Automatic change saving
- **Export Format**: Text, JSON, or both

## 🎮 Usage Tips

### Efficient Workflow
1. **Use Templates**: Start with the Cleric template and modify
2. **Quick Rolls**: Hover over any stat to reveal dice buttons
3. **Batch Editing**: Edit multiple sections at once
4. **Export Regular**: Save character sheets after sessions

### Combat Usage
1. **Roll Initiative**: Click the dice button next to initiative
2. **Track HP**: Click vital stats to quickly adjust HP
3. **Death Saves**: Click dots to mark successes/failures
4. **Conditions**: Toggle conditions as they're applied

### Session Management
1. **Notes**: Keep session notes updated during play
2. **Resources**: Track hit dice and spell slots
3. **Conditions**: Update status effects in real-time
4. **Export**: Generate clean character sheets for records

## 🔧 Technical Details

### Browser Compatibility
- **Chrome**: Full support (recommended)
- **Firefox**: Full support
- **Safari**: Full support
- **Edge**: Full support
- **Mobile Browsers**: Responsive design works on all platforms

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties
- **Vanilla JavaScript**: No frameworks or dependencies
- **Google Fonts**: Cinzel and Crimson Text typography
- **Local Storage**: For settings and data persistence

### File Structure
```
dnd-dashboard.html
├── CSS (embedded)
│   ├── Typography (Google Fonts)
│   ├── Layout (Grid & Flexbox)
│   ├── Theming (CSS Custom Properties)
│   ├── Animations (Smooth transitions)
│   └── Responsive (Mobile-first design)
└── JavaScript (embedded)
    ├── Character Data Management
    ├── Dice Rolling System
    ├── UI State Management
    ├── Settings Persistence
    └── Export Functionality
```

## 🎲 Dice Rolling System

### Supported Rolls
- **Ability Checks**: d20 + ability modifier
- **Skill Checks**: d20 + ability modifier + proficiency (if proficient)
- **Saving Throws**: d20 + ability modifier + proficiency (if proficient)
- **Initiative**: d20 + DEX modifier
- **Hit Dice**: Hit die + CON modifier (minimum 1 HP)
- **Death Saves**: d20 (special rules for nat 1/20)
- **Concentration**: d20 + CON modifier + proficiency (if proficient)

### Roll Features
- **Critical Detection**: Automatic nat 1/20 highlighting
- **Visual Feedback**: Animated popups with results
- **Roll History**: Last 10 rolls tracked in floating widget
- **Modifiers**: Automatic calculation based on character stats

## 📤 Export Format

The export feature generates beautifully formatted text files:

```
════════════════════════════════════════════════════════════
                         THORIN IRONFORGE                          
                   Level 3 Fighter • Lawful Good                   
════════════════════════════════════════════════════════════

                        VITAL STATISTICS                        
                        ────────────────                        
                     Hit Points: 28/28                     
                      Armor Class: 18                      
                        Speed: 25 ft                       
                   Hit Dice: 3/3 d10                   

                        ABILITY SCORES                        
                        ──────────────                        
                      STR: 16 (+3)                      
                      DEX: 13 (+1)                      
                      CON: 15 (+2)                      
                      INT: 10 (+0)                      
                      WIS: 12 (+1)                      
                      CHA: 8 (-1)                       
```

## 🤝 Contributing

This is a single-file web application designed for easy sharing and modification. To contribute:

1. **Fork** or download the HTML file
2. **Make changes** directly in the file
3. **Test** in multiple browsers
4. **Share** your improvements

### Feature Requests
- Spell slot management improvements
- Additional character classes
- Custom dice rolling
- PDF export functionality
- Multiplayer session sharing

## 📜 License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute as needed.

## 🎯 Roadmap

### Coming Soon
- **PDF Export**: Generate printer-friendly character sheets
- **Custom Dice**: Support for weapon damage and custom rolls
- **Character Builder**: Step-by-step character creation wizard
- **Spell Database**: Integrated spell lookup and management
- **Session Sync**: Share character data between devices

### Future Features
- **Campaign Management**: Link multiple characters
- **Digital Dice**: 3D dice rolling animations
- **Voice Commands**: Accessibility through speech recognition
- **Tablet Mode**: Optimized interface for large tablets

## 🆘 Support

### Common Issues
- **Character name not showing**: Refresh the page and try again
- **Dice not rolling**: Check that JavaScript is enabled
- **Settings not saving**: Ensure local storage is enabled
- **Mobile display issues**: Try mobile-friendly mode in settings

### Getting Help
For issues or questions:
1. Check this README for common solutions
2. Verify browser compatibility
3. Try clearing browser cache and refreshing
4. Test in a different browser

---

**Made for D&D players, by D&D players** 🐉

*Happy adventuring!*

---

*Created for the D&D community with ❤️*
