# Claw AI - Local Replica of x.ai

This is a fully functional localhost replica of the x.ai website with your custom Claw.png background.

## Features

✅ **Exact replica of x.ai homepage**
- Navigation bar with logo and menu items
- Large "Claw" hero title with gradient effect
- Search input form with submit button
- Announcement banner at bottom
- Custom background using ~/Downloads/Claw.png

✅ **Interactive Chat Interface**
- Type a question and press Enter or click the up arrow
- Chat interface slides in (similar to how x.ai redirects to grok.com)
- Working AI responses with typing animation
- Multiple pre-programmed responses based on your questions
- Back button to return to homepage

✅ **Responsive Elements**
- Auto-resizing textarea
- Hover effects on buttons
- Smooth animations and transitions
- Typing indicator with animated dots

## How to Use

1. **Open the page**:
   - Double-click `index.html` in Finder
   - Or run: `open ~/Claw/index.html`

2. **Ask a question**:
   - Type in the search box: "What do you want to know?"
   - Press Enter or click the up arrow button

3. **Chat interface**:
   - The chat interface will appear
   - Continue asking questions
   - Click "← Back to Home" to return

## Custom Responses

The AI responds to various questions:
- Greetings (hello, hi)
- "What is AI?"
- "Who are you?" or "What is Claw?"
- "How do you work?"
- And provides intelligent fallback responses for other queries

## Files

- `index.html` - Complete standalone HTML file with CSS and JavaScript
- Background: Uses `~/Downloads/Claw.png` (automatically referenced)

## Customization

To modify the background opacity, edit line 28 in `index.html`:
```css
opacity: 0.3; /* Change this value (0.0 to 1.0) */
```

To change colors or styling, all CSS is embedded in the `<style>` section.

## Technical Details

- Pure HTML/CSS/JavaScript (no external dependencies)
- Works offline
- Responsive design
- Animated typing indicators
- Smooth transitions between home and chat views

Enjoy your Claw AI interface! 🦞
