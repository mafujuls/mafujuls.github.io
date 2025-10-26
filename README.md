# Mafujul Islam - Interactive Terminal Portfolio

An interactive command-line portfolio website inspired by LiveTerm.

## 🚀 Quick Start

```bash
# Test locally
python -m http.server 8000
# Visit: http://localhost:8000
```

## ⌨️ Available Commands

Type these commands in the terminal:

```bash
help          # Show all available commands
about         # About me
whoami        # Quick introduction
experience    # Work history
education     # Educational background
skills        # Technical skills with animated bars
tech          # Technologies, tools & frameworks
contact       # Social media links

# Social Media Commands (opens in new tab)
github        # Open GitHub profile
linkedin      # Open LinkedIn profile
twitter       # Open Twitter profile
instagram     # Open Instagram profile
stackoverflow # Open Stack Overflow profile

# Other Commands
projects      # GitHub projects
clear         # Clear the terminal
history       # Show command history
banner        # Display ASCII art banner
```

## ✨ Features

- ⌨️ **Interactive Terminal Interface** - Type commands to explore
- 🎨 **Animated Skill Bars** - Visual representation of skills
- 📜 **Command History** - Use ↑/↓ arrows to browse previous commands
- ⭐ **Tab Completion** - Start typing and press Tab to auto-complete
- 📱 **Mobile Responsive** - Works perfectly on all devices
- 🎯 **Single File** - Everything in one HTML file
- ⚡ **No Dependencies** - Pure HTML/CSS/JavaScript

## 🎨 Customization

### Change Colors

Edit the CSS variables in `index.html`:

```css
:root {
    --bg: #0d1117;        /* Background */
    --text: #c9d1d9;      /* Text color */
    --green: #39d353;     /* Success/prompt */
    --blue: #58a6ff;      /* Info */
    --cyan: #56d4dd;      /* Highlights */
    --yellow: #f0883e;    /* Warnings */
    --red: #f85149;       /* Errors */
    --gray: #8b949e;      /* Muted text */
}
```

### Add New Commands

Edit the `commands` object in the JavaScript section:

```javascript
commands.mycommand = {
    description: 'Description of command',
    execute: () => {
        return `<div class="success">Your output here</div>`;
    }
};
```

### Update Content

Search for these sections in `index.html` and update with your information:
- `about` command - Your bio and details
- `experience` command - Work history
- `education` command - Educational background
- `skills` command - Technical skills
- `contact` command - Social media links

## 🚀 Deployment

### GitHub Pages

```bash
git init
git add .
git commit -m "Initial commit: Interactive terminal portfolio"
git branch -M main
git remote add origin git@github.com:mafujuls/mafujuls.github.io.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

Your site will be live at: `https://mafujuls.github.io`

### Other Platforms

- **Netlify**: Drag and drop the folder
- **Vercel**: `vercel deploy`
- **Cloudflare Pages**: Connect your repository

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 🎯 Features in Detail

### Command History
- Press ↑ to go back in history
- Press ↓ to go forward in history
- Stores all commands from current session

### Tab Completion
- Start typing a command (e.g., `exp`)
- Press Tab
- Auto-completes to `experience` if it's the only match

### Animated Skills
- Type `skills` to see progress bars
- Bars animate smoothly to their target percentage
- Color gradient from green to cyan

### Click to Focus
- Click anywhere on the page to focus the input
- Seamless typing experience

## 📂 Project Structure

```
.
├── index.html          # Main terminal interface (single file!)
├── README.md           # This file
├── TERMINAL_GUIDE.md   # Detailed guide
├── .gitignore          # Git ignore file
├── backup/             # Old portfolio files (not deployed)
└── assets/             # Assets folder (currently empty)
```

## 💡 Tips

1. The terminal shows a banner on load - customize it in the `banner` command
2. All output uses color-coded classes for visual hierarchy
3. The terminal auto-scrolls to show the latest output
4. Mobile users can tap anywhere to bring up the keyboard

## 🎨 Generate ASCII Art

Visit https://patorjk.com/software/taag/ to create custom ASCII art for your banner.

Recommended fonts:
- ANSI Shadow
- Big
- Standard
- Graffiti

## 📧 Contact

- GitHub: [@mafujuls](https://github.com/mafujuls)
- LinkedIn: [mafujuls](https://linkedin.com/in/mafujuls)

## 📄 License

This project is open source and available under the MIT License.

---

**Made with ❤️ in Germany**
