# Global Force FC Website

## How to Edit Content

### Updating Player Stats
Edit files: `team.html` and `stats.html`
- Look for `&lt;!-- EDIT: ... --&gt;` comments
- Simply replace placeholder text like `[Player Name]` with real names
- Update numbers in the tables for goals/assists

### Updating Fixtures
Edit file: `schedule.html`
- Find `&lt;!-- EDIT: Update these matches --&gt;`
- Change dates, opponent names, and scores

### Adding Photos
1. Create a folder called `assets` in the same directory
2. Put your club logo there as `logo.png`
3. Replace placeholder divs with `&lt;img src="assets/photo.jpg"&gt;`

### Contact Form Setup
1. Go to formspree.io
2. Create a free account
3. Create a new form
4. Replace `YOUR_FORM_ID` in `contact.html` with your actual form ID

### Social Media Links
Find all `YOUR_PAGE` and `YOUR_ACCOUNT` placeholders and replace with your actual Facebook/TikTok URLs.
