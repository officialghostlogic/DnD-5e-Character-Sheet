# D&D 5e Character Dashboard

A modern, interactive web-based character sheet for Dungeons & Dragons 5th Edition with **automatic local storage** and **full offline functionality**. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and ease of use.

![Character Dashboard Preview](https://via.placeholder.com/800x400/6b4423/f4f1e8?text=D%26D+5e+Character+Dashboard)

## ✨ Key Features

### 💾 **Smart Data Management**
- **Auto-Save**: All changes automatically saved to your browser
- **Local Storage**: Works completely offline, no internet required
- **Import/Export**: Share characters via JSON files
- **Cross-Device**: Move characters between devices easily
- **Data Safety**: Your character data never leaves your device

### 🎲 **Interactive Dice Rolling**
- **One-click dice rolls** for ability checks, skills, saves, and combat
- **Visual roll results** with critical hit/fumble detection
- **Roll history tracker** with floating widget
- **Animated roll popups** with customizable settings

### 📊 **Complete Character Management**
- **Vital Statistics**: HP tracking with visual bar, AC, speed
- **Ability Scores**: All six abilities with modifier calculation
- **Combat Tracking**: Initiative, proficiency, hit dice, death saves
- **Skills & Saves**: Proficiency tracking with auto-calculated bonuses
- **Spellcasting**: Spell slots, known spells, concentration tracking
- **Equipment**: Inventory management with currency tracking
- **Conditions**: Status effect tracking with common D&D conditions
- **Notes**: Session notes, character backstory, plot reminders

### 🎨 **Modern Design**
- **Glassmorphism UI** with elegant transparency effects
- **Fantasy Theming** with custom fonts (Cinzel & Crimson Text)
- **Responsive Layout** that works on desktop, tablet, and mobile
- **Dark/Light Themes** with smooth transitions
- **Hover Effects** and smooth animations throughout

### ♿ **Accessibility Features**
- **Font Size Controls** (Small, Normal, Large, Extra Large)
- **High Contrast Mode** for improved visibility
- **Reduced Motion** option for sensitive users
- **Enhanced Keyboard Navigation** with tab support
- **Mobile-Friendly Mode** with larger touch targets
- **Screen Reader Compatible** with proper ARIA labels

## 🚀 Getting Started

### Quick Start
1. **Download** the HTML file
2. **Open** in any modern web browser
3. **Start playing!** Your character automatically saves

### First Time Setup
1. **Create Character**: Edit sections by clicking any card
2. **Customize Settings**: Click ⚙️ Settings for accessibility options
3. **Start Rolling**: Hover over stats to reveal dice buttons
4. **Auto-Save**: Everything saves automatically as you play

## 💾 Data Management

### **Automatic Saving**
Your character data is **automatically saved** to your browser's local storage:
- ✅ **Every edit** is instantly saved
- ✅ **Settings** are preserved between sessions
- ✅ **Roll history** is maintained
- ✅ **Works offline** - no internet required

### **Manual Controls**
- **💾 Save**: Force save current state (header button)
- **📥 Import**: Load character from JSON file (header button)
- **📤 Export**: Save as formatted text file (header button)
- **📄 Export JSON**: Save character data file (settings menu)

### **Cross-Device Sharing**
1. **Export JSON** from settings or use 📄 Export JSON
2. **Transfer file** to another device (email, cloud, USB)
3. **Import JSON** on new device using 📥 Import button
4. **Character appears** with all data intact

### **Data Safety**
- **🔒 Local Only**: Data stays in your browser, never uploaded
- **🚫 No Account**: No registration or login required
- **📱 Offline Ready**: Works without internet connection
- **💼 Backup Friendly**: Export JSON files for safe keeping

## 🎯 Core Sections

### ⚡ Vital Stats
- Current/Max HP with visual health bar
- Armor Class and Speed tracking
- Color-coded health status (green/yellow/red)
- **Auto-saved** on every change

### 💪 Ability Scores
- All six D&D abilities (STR, DEX, CON, INT, WIS, CHA)
- Automatic modifier calculation
- One-click ability check rolling
- **Proficiency bonuses** calculated automatically

### ⚔️ Combat
- Initiative tracking with DEX modifier
- Proficiency bonus calculation by level
- Hit dice management with healing rolls
- Death saving throws with success/failure tracking
- Saving throw proficiencies
- **Real-time updates** during combat

### 🎯 Skills & Saves
- Skill proficiency tracking
- Automatic bonus calculation (ability + proficiency)
- Quick skill check rolling
- Saving throw proficiency management
- **Visual indicators** for proficient skills

### ✨ Spells & Magic
- Spellcasting ability selection
- Spell slot tracking by level
- Known spells list management
- Concentration tracking with automatic save rolling
- **Spell slot recovery** tracking

### 🎒 Equipment
- Item inventory with quantity, weight, and notes
- Currency tracking (CP, SP, GP, PP)
- Equipment notes for stats and special properties
- **Automatic weight calculation** (if desired)

### 🔥 Conditions & Status
- Inspiration tracking with visual indicator
- Concentration management with spell tracking
- Common D&D conditions (Blinded, Charmed, etc.)
- Quick condition toggle interface
- **Status effect reminders**

### 📝 Notes & Reminders
- Session notes for what happened during play
- Character notes for backstory and personality
- Plot reminders for important NPCs and story threads
- **Rich text support** for detailed notes

## ⚙️ Settings & Customization

### 🎨 Visual Settings
- **Font Size**: 4 size options (Small to Extra Large)
- **High Contrast**: Black/white mode for better visibility
- **Reduced Motion**: Disables animations for accessibility
- **Theme Toggle**: Dark/Light mode switching

### 🎲 Dice Settings
- **Roll Sounds**: Audio feedback for dice rolls (coming soon)
- **Auto-roll Hover**: Show/hide dice buttons on hover
- **Roll Confirmation**: Confirm before rolling dice
- **Roll History**: Persistent roll tracking

### 🖱️ Interaction Settings
- **Click Feedback**: Visual button press feedback
- **Keyboard Navigation**: Enhanced tab navigation
- **Tooltip Delays**: Customizable hover delays
- **Touch Optimization**: Mobile-friendly interactions

### 📱 Mobile Settings
- **Mobile-Friendly Mode**: Larger touch targets and simplified UI
- **Swipe Navigation**: Gesture support (coming soon)
- **Responsive Design**: Adapts to all screen sizes

### 💾 Data Settings
- **Auto-Save**: Toggle automatic saving (recommended: ON)
- **Export Format**: Choose default export format
- **Data Management**: Clear, import, export controls
- **Version Tracking**: Future-proof data format

## 🎮 Usage Guide

### **Starting Fresh**
1. **Open** the dashboard in your browser
2. **Click any card** to start editing that section
3. **Begin with basics**: Name, class, level, abilities
4. **Add details**: Skills, equipment, spells as needed
5. **Everything saves automatically**

### **During Game Sessions**
1. **Roll dice** by hovering over stats and clicking 🎲
2. **Track HP** by clicking Vital Stats card
3. **Manage resources** using hit dice and spell slot tracking
4. **Update conditions** in real-time during combat
5. **Take notes** throughout the session

### **Between Sessions**
1. **Review notes** from last session
2. **Level up** by editing Combat section
3. **Manage equipment** and treasure
4. **Plan character development**
5. **Export for backup** if desired

### **Sharing Characters**
1. **Settings → Export JSON** to save character file
2. **Share file** with DM or other players
3. **Import on other devices** using 📥 Import button
4. **Collaborate** on character builds

## 🎲 Dice Rolling System

### **Supported Rolls**
- **Ability Checks**: d20 + ability modifier
- **Skill Checks**: d20 + ability modifier + proficiency (if proficient)
- **Saving Throws**: d20 + ability modifier + proficiency (if proficient)
- **Initiative**: d20 + DEX modifier
- **Hit Dice**: Hit die + CON modifier (minimum 1 HP)
- **Death Saves**: d20 (special rules for natural 1/20)
- **Concentration**: d20 + CON modifier + proficiency (if proficient)

### **Roll Features**
- **Critical Detection**: Automatic natural 1/20 highlighting
- **Visual Feedback**: Animated popups with results
- **Roll History**: Last 10 rolls tracked in floating widget
- **Modifier Display**: Shows breakdown of bonuses
- **Auto-Calculation**: All modifiers computed automatically

## 📤 Export Formats

### **Text Export** (Beautiful formatted sheets)
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

### **JSON Export** (Data interchange)
```json
{
  "character": {
    "name": "Thorin Ironforge",
    "class": "Fighter",
    "level": 3,
    "abilities": {
      "str": 16,
      "dex": 13,
      "con": 15
    }
  },
  "settings": {
    "fontSize": "normal",
    "autoSave": true
  },
  "exportDate": "2024-01-15T10:30:00Z",
  "version": "1.0"
}
```

## 🔧 Technical Details

### **Browser Compatibility**
- ✅ **Chrome**: Full support (recommended)
- ✅ **Firefox**: Full support
- ✅ **Safari**: Full support
- ✅ **Edge**: Full support
- ✅ **Mobile Browsers**: Responsive design works everywhere

### **Storage Requirements**
- **Local Storage**: ~1-5MB per character (tiny!)
- **No Internet**: Works completely offline
- **No Servers**: Everything runs in your browser
- **No Accounts**: No registration required

### **Technologies Used**
- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with custom properties
- **Vanilla JavaScript**: No frameworks, maximum compatibility
- **Web Storage API**: For persistent character data
- **Google Fonts**: Beautiful typography (Cinzel & Crimson Text)

### **Data Format**
```
Character Dashboard Data Structure:
├── Character Data
│   ├── Basic Info (name, class, level)
│   ├── Abilities & Modifiers
│   ├── Combat Stats (HP, AC, saves)
│   ├── Skills & Proficiencies
│   ├── Equipment & Currency
│   ├── Spells & Magic
│   ├── Conditions & Status
│   └── Notes & Reminders
├── Settings & Preferences
├── Roll History
└── Metadata (version, timestamps)
```

## 🛡️ Data Privacy & Security

### **Your Data Stays Private**
- 🔒 **Local Storage Only**: Data never leaves your device
- 🚫 **No Cloud Storage**: We don't store anything on servers
- 🔐 **No Tracking**: No analytics or data collection
- 📱 **Offline First**: Works without internet connection

### **Data Control**
- **You Own It**: Complete control over your character data
- **Export Anytime**: Take your data wherever you want
- **Delete Anytime**: Clear all data with one button
- **No Lock-in**: Standard JSON format for portability

## 🆘 Troubleshooting

### **Common Issues**

**Character data not saving?**
- ✅ Check that JavaScript is enabled
- ✅ Ensure local storage is not disabled
- ✅ Try clearing browser cache and refreshing
- ✅ Check available storage space

**Dice not rolling?**
- ✅ Verify JavaScript is enabled
- ✅ Try hovering over stats to reveal dice buttons
- ✅ Check if reduced motion is enabled in settings

**Import not working?**
- ✅ Ensure file is valid JSON format
- ✅ Check file was exported from this dashboard
- ✅ Try a different browser
- ✅ Verify file isn't corrupted

**Display issues on mobile?**
- ✅ Enable mobile-friendly mode in settings
- ✅ Try rotating device orientation
- ✅ Check font size settings
- ✅ Clear browser cache

### **Browser Storage Limits**
- Most browsers allow 5-10MB local storage
- Each character uses ~1-5MB (very small!)
- Can store hundreds of characters typically
- Export JSON files for long-term storage

### **Getting Help**
For additional support:
1. Check browser console for error messages
2. Try the dashboard in a different browser
3. Export your character data before troubleshooting
4. Clear browser data as a last resort

## 🛣️ Roadmap

### **Coming Soon** (v1.1)
- 🔊 **Sound Effects**: Dice rolling audio feedback
- 📋 **Multiple Templates**: Fighter, Wizard, Rogue, etc.
- 🎨 **Custom Themes**: Personalize colors and styling
- 📱 **PWA Support**: Install as a mobile app

### **Future Features** (v2.0)
- 📄 **PDF Export**: Generate printer-friendly character sheets
- 🎲 **Custom Dice**: Support for weapon damage and custom rolls
- 👥 **Party Mode**: Link multiple characters in a campaign
- 📚 **Spell Database**: Integrated D&D spell lookup
- 🗺️ **Campaign Notes**: Link characters to campaign data

### **Advanced Features** (v3.0)
- 🌐 **Sync Options**: Optional cloud sync between devices
- 🤖 **Character Builder**: Step-by-step creation wizard
- 📊 **Statistics**: Track rolls, combat performance
- 🎮 **VTT Integration**: Connect to virtual tabletops

## 🤝 Contributing

This is a single-file web application designed for easy sharing and modification.

### **How to Contribute**
1. **Download** the HTML file
2. **Make improvements** directly in the file
3. **Test thoroughly** across browsers
4. **Share** your enhanced version

### **Feature Requests**
Have ideas? We'd love to hear them:
- Enhanced spell management
- Additional character races/classes
- Custom dice rolling features
- Integration with D&D Beyond
- Accessibility improvements

## 📜 License

**MIT License** - Open source and free to use, modify, and distribute.

### **What this means:**
- ✅ Use for personal games
- ✅ Modify for your table's needs
- ✅ Share with your gaming group
- ✅ Host on your own website
- ✅ Create derivative works

## 🎲 Final Notes

### **Perfect For:**
- **New Players**: Simple, guided character management
- **Experienced Players**: Advanced features and customization
- **DMs**: Quick NPC creation and management
- **Groups**: Easy character sharing and collaboration
- **Solo Players**: Offline character development

### **Why Choose This Dashboard:**
- 🚀 **No Setup**: Works immediately in any browser
- 💾 **Reliable**: Automatic saving prevents data loss
- 🔒 **Private**: Your data stays on your device
- 📱 **Portable**: Works on phone, tablet, desktop
- 🎯 **D&D Focused**: Built specifically for 5e rules

---

**Ready to roll for initiative?** 🎲

Download the dashboard and start your adventure today!

*Made with ❤️ for the D&D community*# D&D 5e Character Dashboard

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
