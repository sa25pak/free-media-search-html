# Free Media Search - HTML Version

A simple, single-file HTML webpage application to search for high-quality, copyright-free images and videos across multiple free stock media websites including Unsplash, Pexels, and Pixabay.

![Free Media Search](https://images.unsplash.com/photo-1611224923853-80b023f02d71?w=800&q=80)

## ✨ Features

🔍 **Multi-Source Search** - Search across Unsplash, Pexels, and Pixabay simultaneously
🖼️ **Images & Videos** - Toggle between image and video search
📱 **Fully Responsive** - Works on desktop, tablet, and mobile
⚡ **Zero Setup** - Just open the HTML file in your browser
🎨 **Modern Design** - Clean interface with Tailwind CSS
📥 **One-Click Downloads** - Easy download functionality
🏷️ **License Information** - Clear licensing details for each item

## 🚀 Quick Start

### Option 1: Basic Usage (No API Keys - Limited Functionality)
1. Download the `index.html` file
2. Open it in any modern web browser
3. The app will show a setup message about API keys

### Option 2: Full Setup (Recommended)
1. **Get Free API Keys** (all free, takes 5 minutes):
   - **Unsplash**: Visit [unsplash.com/developers](https://unsplash.com/developers) → Create App → Copy Access Key
   - **Pexels**: Visit [pexels.com/api](https://www.pexels.com/api/) → Sign up → Get API Key
   - **Pixabay**: Visit [pixabay.com/api/docs](https://pixabay.com/api/docs/) → Sign up → Get API Key

2. **Update the HTML file**:
   - Open `index.html` in a text editor
   - Find the API configuration section (around line 228)
   - Replace the placeholder keys:
   ```javascript
   const API_CONFIG = {
       unsplash: {
           key: 'YOUR_ACTUAL_UNSPLASH_ACCESS_KEY_HERE',
           url: 'https://api.unsplash.com/search/photos'
       },
       pexels: {
           key: 'YOUR_ACTUAL_PEXELS_API_KEY_HERE',
           imageUrl: 'https://api.pexels.com/v1/search',
           videoUrl: 'https://api.pexels.com/videos/search'
       },
       pixabay: {
           key: 'YOUR_ACTUAL_PIXABAY_API_KEY_HERE',
           imageUrl: 'https://pixabay.com/api/',
           videoUrl: 'https://pixabay.com/api/videos/'
       }
   };
   ```

3. **Open the HTML file** in any modern web browser

## 📖 How to Use

1. **Search**: Type keywords into the search bar or click popular suggestions
2. **Filter**: Use the Images/Videos tabs to switch content types
3. **Browse**: Scroll through the responsive grid of results
4. **View Details**: Hover over items to see action buttons
5. **Download**: Click "Download" to save high-quality files
6. **Source**: Click "View Source" to visit the original page

## 🔧 Technical Details

- **Single File**: Everything in one HTML file - no build process needed
- **CDN Dependencies**: Uses Tailwind CSS from CDN
- **Vanilla JavaScript**: No frameworks, works in any modern browser
- **CORS Enabled APIs**: Works with browser-friendly APIs
- **Responsive Design**: Mobile-first, responsive grid layout
- **Error Handling**: Graceful error handling for API failures

## 🌐 Browser Compatibility

Works in all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License Information

**Application**: Free to use and modify
**Media Sources**:
- Unsplash: Free for commercial and personal use
- Pexels: Free for commercial and personal use
- Pixabay: Free for commercial and personal use

*Always check individual licenses before commercial use.*

## 🔒 Privacy & Security

- No data is stored locally or sent to third parties
- API keys are only used for direct communication with media services
- All searches are performed directly in your browser

## 🆘 Troubleshooting

**"Setup Required" message appears**:
- You need to add your API keys (see setup instructions above)

**No results found**:
- Check your internet connection
- Verify API keys are correct
- Try different search terms
- Some terms may not have results in all sources

**Download not working**:
- Some browsers block automatic downloads
- Try right-clicking and selecting "Save as"
- Check if the original URL is accessible

**CORS errors in browser console**:
- This is expected behavior when API keys are not configured
- The APIs used support CORS for browser-based applications

## 🎯 Why This HTML Version?

✅ **Simple**: One file, no installation or build process
✅ **Fast**: Instant setup, just open in browser
✅ **Portable**: Works offline once loaded (with cached assets)
✅ **Customizable**: Easy to modify and style
✅ **No Dependencies**: Doesn't require Node.js or package managers

Perfect for:
- Quick prototypes and demos
- Educational purposes
- Simple integration into existing websites
- Users who prefer simple solutions

## 🚀 Advanced Usage

Want to integrate this into your website? Simply:
1. Copy the HTML content
2. Extract the CSS and JavaScript into separate files if desired
3. Customize the styling and functionality as needed
4. Host on any web server or CDN

The code is clean, well-commented, and easy to extend with additional features or media sources.

---

**Ready to find amazing free media?** Just open the HTML file and start searching! 🎉
