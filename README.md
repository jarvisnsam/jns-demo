# Smartgent Enterprise AI Input Assistance - Mockup Site

## Overview
Professional mockup site showcasing Smartgent's Enterprise AI Input Assistance platform with three key use cases designed for different enterprise departments.

## Live Demo
Host this on GitHub Pages at: `https://[your-username].github.io/smartgent-demo/`

## Features

### 🎯 Three Enterprise Solutions

1. **ExpenseIQ™** - Finance & Operations
   - Transform receipts into instant expense reports
   - Auto-categorization and approval routing
   
2. **LeaveSync™** - HR & Employee Services  
   - Auto-generate leave requests from travel documents
   - Intelligent date extraction and calendar integration

3. **TalentMatch™** - HR & Talent Acquisition
   - AI-powered candidate scoring and job matching
   - Skill extraction and compatibility analysis

### 🎬 Dual Viewing Modes

- **Manual Mode**: Click-through presentation for live demos
- **Auto-Play Mode**: Timed slideshow perfect for screen recording (30-second loop)

### 📐 Technical Specifications

- **Aspect Ratio**: 16:9 (1920x1080) optimized for video recording
- **Technology**: Static HTML + CSS3 Animations + Vanilla JavaScript
- **Hosting**: GitHub Pages compatible
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## Scene Flow (Auto-Play Timing)

| Scene | Duration | Content |
|-------|----------|---------|
| Hero Landing | 0-3s | Logo animation, tagline, 3 use case cards |
| ExpenseIQ Demo | 3-10s | Receipt upload → AI processing → Expense report |
| LeaveSync Demo | 10-17s | Flight ticket → Date extraction → Leave form |
| TalentMatch Demo | 17-24s | Resume upload → Skill matching → Score display |
| ROI Dashboard | 24-28s | Animated statistics and metrics |
| Call to Action | 28-30s | Final message with contact button |

## Video Recording Tips

1. Set browser to full screen (F11)
2. Click "Start Auto-Play" button
3. Begin screen recording
4. Site will loop automatically every 30 seconds
5. Recommended: Record 2 loops, use best take

## Customization Guide

### Replacing Placeholder Images

1. **Logo**: Replace `smartgent-logo` SVG in index.html
2. **Receipt**: Add actual receipt image to ExpenseIQ section
3. **Flight Ticket**: Add boarding pass image to LeaveSync section
4. **Resume**: Add CV sample to TalentMatch section

### Modifying Timing

Edit `SCENE_DURATIONS` in `script.js`:
```javascript
const SCENE_DURATIONS = {
    hero: 3000,      // 3 seconds
    expense: 7000,   // 7 seconds
    leave: 7000,     // 7 seconds
    talent: 7000,    // 7 seconds
    roi: 4000,       // 4 seconds
    cta: 2000        // 2 seconds
};
```

### Color Scheme

Primary colors defined in `styles.css`:
- Primary Blue: `#2563eb`
- Secondary Purple: `#7c3aed`
- Success Green: `#10b981`
- Background: `#f8fafc`

## Deployment to GitHub Pages

1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select Source: Deploy from branch
4. Select Branch: main (or master)
5. Select Folder: / (root)
6. Save and wait 2-3 minutes
7. Access at: `https://[username].github.io/[repository-name]/`

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Performance Metrics

- Page Load: < 1 second
- Animation FPS: 60fps
- Total Size: < 500KB
- No external dependencies

## License

This is a mockup/demo site for presentation purposes.

---

Built with ❤️ for Smartgent Enterprise AI Solutions
