# DevCard - Developer ID Card Generator

A beautiful, modern web application that generates stunning visual ID cards for GitHub profiles. Perfect for sharing your GitHub stats on social media, portfolios, or with your team.

## ✨ Features

### 📊 Comprehensive Statistics
- **Profile Overview**: Avatar, name, username, bio, and account metadata
- **Key Metrics**: Public repos, total stars, followers, following, forks, and gists
- **Language Breakdown**: Top 5 programming languages with visual progress bars
- **Contribution Stats**: Open issues, original vs forked repos, and average repository size
- **Popular Topics**: Top 10 most-used repository topics/tags
- **Featured Repository**: Highlights your most starred repository

### 🎨 Beautiful Design
- **Developer-Focused UI**: Clean, modern design with glassmorphism effects
- **Dark Theme**: Eye-friendly dark mode with vibrant accent colors
- **Responsive Layout**: Perfectly optimized for mobile, tablet, and desktop
- **Professional Icons**: SVG icons throughout for crisp, scalable graphics
- **Screenshot-Ready**: Compact layout ideal for social media sharing

### 🚀 Powerful Features
- **High-Quality Export**: Download profile card as PNG (3x resolution for crystal-clear quality)
- **URL Sharing**: Generate shareable links with pre-loaded profiles
- **Real-Time Data**: Fetches live data directly from GitHub API
- **Account Badges**: Shows account type (Pro/Organization), account age, hireable status
- **Timestamps**: Displays when data was fetched and when profile was last updated
- **Direct Links**: Quick access to GitHub profile and social media

### 📱 Smart Functionality
- **Auto-Load from URL**: Share links like `?user=username` to load profiles automatically
- **Error Handling**: User-friendly error messages for invalid usernames
- **Loading States**: Visual feedback during data fetching
- **Success Animations**: Confirmation animations for download and share actions

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, animations, and gradients
- **Vanilla JavaScript**: Pure JS with async/await for API calls
- **GitHub REST API**: Real-time data fetching
- **html2canvas**: High-quality screenshot generation

## 🎯 Use Cases

- **Social Media**: Share your GitHub stats on Twitter, LinkedIn, or Instagram
- **Portfolio**: Embed your GitHub card in your personal website
- **Team Profiles**: Showcase team members' GitHub contributions
- **README Files**: Add your stats card to your GitHub profile README
- **Presentations**: Include developer profiles in presentations or reports

## 📖 How to Use

### Option 1: Direct Usage (Recommended)

1. **Download the file**: Save `devcard.html` to your computer
2. **Open in browser**: Double-click the file to open it in any modern web browser
3. **Enter username**: Type any GitHub username and click "Generate"
4. **Download or share**: Use the buttons at the bottom to download or share the profile

### Option 2: Host on Web Server

```bash
# Clone or download the repository
git clone <repository-url>

# Navigate to the directory
cd "DevCard"

# Serve with any static server (examples below)

# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000/devcard.html` in your browser.

### Option 3: Share Direct Links

Share profiles with pre-loaded data using URL parameters:

```
devcard.html?user=torvalds
devcard.html?user=github
```

## 🎨 Features Breakdown

### Profile Card Includes:

#### Header Section
- Profile avatar with glowing border
- Full name and username
- Account badges (Organization, Pro User, Age, Hireable, Gists)
- Bio/description
- Contact information (Email, Location, Company, Website, Twitter)

#### Statistics Grid
- Public Repositories count
- Total Stars across all repos
- Follower count
- Following count
- Total Forks
- Public Gists count

#### Language Analysis
- Top 5 programming languages
- Visual progress bars with percentages
- Color-coded by language

#### Contribution Insights
- Total open issues
- Original repositories count
- Forked repositories count
- Average repository size

#### Popular Topics
- Top 10 repository topics/tags
- Interactive hover effects
- Repository count per topic

#### Featured Repository
- Most starred repository highlighted
- Full description and stats
- Direct link to repository

#### Top Repositories
- 9 most starred repositories
- Language, stars, and forks for each
- Click to open on GitHub

#### Actions
- Search another profile
- Download card as high-quality PNG
- View profile on GitHub
- Share profile with unique URL

## 🎨 Customization

The app uses CSS custom properties for easy theme customization. Edit these variables in the `<style>` section:

```css
:root {
    --bg-primary: #0a0e27;
    --accent-blue: #6366f1;
    --accent-green: #3fb950;
    --accent-purple: #bc8cff;
    --accent-orange: #ffa657;
    --accent-pink: #ec4899;
    --accent-red: #ff7b72;
}
```

## 📊 API Rate Limits

The app uses the GitHub REST API v3. Rate limits:

- **Unauthenticated requests**: 60 requests per hour per IP
- **Authenticated requests**: 5,000 requests per hour

For higher rate limits, you can add a GitHub token (requires code modification).

## 🔒 Privacy & Security

- **No data storage**: All data is fetched in real-time and not stored
- **Client-side only**: Everything runs in your browser
- **No tracking**: No analytics or user tracking
- **Open source**: All code is visible and auditable

## 🌐 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 📱 Responsive Design

Optimized breakpoints:
- **Desktop**: 1200px+ (full layout)
- **Tablet**: 768px - 1199px (adapted layout)
- **Mobile**: < 768px (stacked layout)

## 🐛 Known Limitations

1. **API Rate Limits**: Limited to 60 requests per hour without authentication
2. **Public Profiles Only**: Can only fetch data from public GitHub profiles
3. **Repository Limit**: Fetches up to 100 repositories per user
4. **Topics Support**: Only shows topics if repositories have topics added

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Bugs**: Open an issue describing the bug
2. **Suggest Features**: Share your ideas for new features
3. **Submit PRs**: Fork the repo and submit pull requests
4. **Improve Docs**: Help improve documentation

### Development Setup

```bash
# No build process required!
# Just edit devcard.html and refresh your browser
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **GitHub API**: For providing comprehensive profile data
- **html2canvas**: For enabling high-quality image exports
- **GitHub Community**: For language colors and design inspiration

## 📬 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) page for existing solutions
2. Open a new issue with detailed information
3. Include browser version and error messages if applicable

## 🌟 Show Your Support

If you find this project useful:

- ⭐ Star the repository
- 🐦 Share on social media
- 🔗 Link to it from your projects
- 💬 Spread the word!

## 📸 Screenshots

The app generates beautiful, compact ID cards perfect for:
- Social media posts
- GitHub profile READMEs
- Portfolio websites
- Team directories
- Developer presentations

---

**Made with ❤️ for developers**

*Powered by GitHub REST API*
