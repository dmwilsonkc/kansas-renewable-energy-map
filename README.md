# Kansas Renewable Energy Moratoriums - Interactive Map

An interactive web-based map displaying renewable energy development moratoriums and restrictions across all 105 Kansas counties.

## 🌐 Live Map

**View the interactive map:** [https://dmwilsonkc.github.io/kansas-renewable-energy-map/](https://dmwilsonkc.github.io/kansas-renewable-energy-map/)

*(Replace `yourusername` with your actual GitHub username)*

## 📊 About This Project

This interactive map provides comprehensive data on wind and solar energy development restrictions across Kansas, including:

- **35 counties** with documented moratoriums or bans
- **15 active moratoriums** currently in effect
- **6 permanent bans** on renewable energy development
- **12 Flint Hills counties** with state-level Tallgrass Heartland Wind Moratorium protection

### Data Categories

- 🔴 **Permanent Bans** - Counties with indefinite prohibitions
- 🔴 **Active Moratoriums** - Both wind and solar restricted
- 🔴 **Partial Moratoriums** - Either wind or solar restricted
- 🟠 **State Protection** - Tallgrass Heartland areas
- 🟡 **Expired Moratoriums** - Previously restricted, now lifted
- 🟢 **No Restrictions** - Open to renewable development
- ⚫ **Insufficient Data** - Limited public information available

## 🗺️ Features

- **Interactive County Selection** - Click any county for detailed information
- **Color-Coded Status** - Visual representation of restriction types
- **Comprehensive Data** - Wind and solar moratorium dates and status
- **Source Links** - Direct links to official documentation
- **Mobile Responsive** - Works on desktop, tablet, and mobile devices

## 🔄 How to Update the Map

### Updating Data

1. Open `index.html` in a text editor
2. Find the `countyData` object (around line 150)
3. Update county information following this format:

```javascript
'CountyName': { 
    wind: 'Status', 
    windDates: 'Date range', 
    solar: 'Status', 
    solarDates: 'Date range', 
    source: 'https://source-url.com', 
    status: 'category' 
}
```

4. Status categories: `ban`, `active-both`, `active-partial`, `state`, `expired`, `none`, `insufficient`
5. Save the file
6. Commit and push changes to GitHub

### The map will automatically update within 1-2 minutes!

## 📝 Data Sources

All moratorium data is sourced from:
- County government websites and official resolutions
- Local news reports and press releases
- Kansas state government announcements
- Public records and meeting minutes

Each county entry includes links to source documentation for verification.

## 🛠️ Technical Details

**Built with:**
- [Leaflet.js](https://leafletjs.com/) - Interactive mapping library
- [OpenStreetMap](https://www.openstreetmap.org/) - Base map tiles
- GeoJSON county boundaries from US Census Bureau
- Pure HTML/CSS/JavaScript (no build process required)

**Browser Compatibility:**
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This data compilation is provided for informational purposes. Please verify current status with individual county authorities before making business or legal decisions.

Data accuracy as of: **September 29, 2025**

## 🤝 Contributing

Found an error or have updated information? 

1. Open an Issue with the county name and corrected information
2. Include a link to the source documentation
3. Or submit a Pull Request with the updated data

## 📧 Contact

For questions or corrections, please open an issue in this repository.

---

**Note:** This is a research compilation. Always verify current regulations with county planning and zoning departments before proceeding with renewable energy projects.
