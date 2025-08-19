# Charleston School of Law - SIS Evaluation Toolkit 2025

## 📋 Overview

This repository contains two powerful tools for evaluating Student Information System (SIS) vendors for Charleston School of Law's 650-student institution:

1. **SIS RFP Template Generator** - Create and manage Request for Proposal documents
2. **SIS Vendor KPI Dashboard** - Track, compare, and analyze vendor submissions with interactive visualizations

Both tools are completely client-side (no server required) and store data locally in your browser.

## 🚀 Quick Start

### Live Demo
Visit: `https://ajgcsol.github.io/` (after deployment)

### Tools Available

#### 1. RFP Generator (`sis-rfp-generator.html`)
- Generate comprehensive RFP documents for vendors
- Export templates to Excel for vendor completion
- Track vendor responses and notes
- Compare multiple vendor submissions
- Calculate 5-year and 10-year TCO

#### 2. KPI Dashboard (`sis-kpi-dashboard.html`)
- Interactive vendor comparison dashboard
- Real-time cost analysis and visualizations
- Industry benchmarking for law schools
- Export comprehensive comparison reports
- Share forms with vendors for direct submission

## 📖 How to Use

### For Institution Staff

#### Using the RFP Generator:

1. **Create an RFP:**
   - Open `sis-rfp-generator.html`
   - Fill in your institution information
   - Set the RFP due date
   - Click "Generate RFP Document"
   - Download or copy the generated RFP text

2. **Generate Excel Template:**
   - Click "Generate Excel Template"
   - This creates a structured Excel file vendors can fill out
   - Send this to vendors along with the RFP document

3. **Track Vendor Responses:**
   - Enter vendor responses in the form
   - Add timestamped notes for each vendor
   - Click "Save Vendor Response" to store locally
   - Use "Compare Vendors" to see side-by-side analysis

#### Using the KPI Dashboard:

1. **Submit Vendor Data:**
   - Go to the "Vendor Submission" tab
   - Enter vendor pricing and details
   - Add notes from multiple team members
   - Save each vendor submission

2. **View Analytics:**
   - Dashboard tab shows real-time KPIs
   - Automatic calculation of averages and trends
   - Interactive charts for cost comparison
   - 5-year TCO analysis

3. **Compare Vendors:**
   - "Comparison Matrix" tab shows detailed side-by-side
   - Export to Excel for offline analysis
   - Generate reports for stakeholders

### For SIS Vendors

#### Submitting Your Proposal:

1. **Via Excel Template:**
   - Request the Excel RFP template from the institution
   - Fill in all requested fields
   - Return completed Excel file

2. **Via Online Form:**
   - Access the shared link provided by the institution
   - Go to "Vendor Submission" tab
   - Complete all fields with accurate information
   - Submit your response

## 💾 Data Management

### Data Storage
- All data is stored locally in your browser (localStorage)
- No data is sent to external servers
- Data persists between sessions on the same device

### Backup & Sharing
- **Export to Excel:** Both tools support Excel export
- **JSON Backup:** Dashboard allows JSON export/import
- **Clear Data:** Option to reset all stored information

## 📊 Key Features

### RFP Generator Features:
- ✅ Pre-configured for 650-student law school
- ✅ Comprehensive vendor evaluation criteria
- ✅ Training requirements calculator
- ✅ Multi-user note system
- ✅ Excel template generation
- ✅ Vendor comparison matrix

### KPI Dashboard Features:
- ✅ Real-time analytics
- ✅ Industry benchmarking
- ✅ Interactive Plotly charts
- ✅ 5-year TCO calculations
- ✅ Cloud vs on-premise analysis
- ✅ Implementation timeline tracking
- ✅ Hidden costs estimation

## 🏷️ Typical Pricing Ranges (Law Schools 500-1000 students)

| Component | Low End | Average | High End |
|-----------|---------|---------|----------|
| Annual License | $100K | $175K | $250K+ |
| Implementation | $150K | $250K | $400K+ |
| 5-Year TCO | $650K | $1.1M | $1.5M+ |
| Timeline | 6 months | 9 months | 12+ months |

## 🔧 Technical Requirements

### Browser Requirements:
- Modern browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- localStorage enabled
- Internet connection (for CDN libraries only)

### No Installation Required:
- Open HTML files directly in browser
- Or host on GitHub Pages
- No server-side setup needed

## 📁 Repository Structure

```
/
├── index.html (or redirect)
├── sis-rfp-generator.html
├── sis-kpi-dashboard.html
├── _config.yml (GitHub Pages config)
└── README.md (this file)
```

## 🚀 Deployment to GitHub Pages

1. **Fork or Clone Repository**
2. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Source: Deploy from branch
   - Branch: main (or master)
   - Folder: / (root)
3. **Access Your Site:**
   - URL: `https://[your-username].github.io/[repository-name]/`

## 📝 Important Notes

### For Institutions:
- Verify all vendor submissions independently
- Request formal documentation for all claims
- Consider conducting POCs (Proof of Concepts)
- Include legal/compliance review
- Budget for hidden costs (typically 20-30% above quoted prices)

### For Vendors:
- Provide transparent, all-inclusive pricing
- Include all required modules for law school operations
- Specify any third-party costs (databases, integrations)
- Be clear about implementation timelines
- List all training requirements

## 🔐 Security & Privacy

- **No Data Transmission:** All data stays in your browser
- **Local Storage Only:** Data is not sent to any server
- **Manual Sharing:** You control what data to export/share
- **Clear Anytime:** Full control to delete all stored data

## 📧 Support

For questions about:
- **RFP Process:** Contact your institution's IT department
- **Technical Issues:** Check browser console for errors
- **Data Questions:** Verify with vendors directly

## 📄 License

This toolkit is provided as-is for educational evaluation purposes. Institutions should conduct their own due diligence when selecting SIS vendors.

## 🎯 Quick Actions

### First Time Users:
1. Start with the KPI Dashboard
2. Use "Auto-Fill Realistic Example" to see sample data
3. Explore the visualizations
4. Clear data and begin your evaluation

### Returning Users:
1. Check the dashboard for saved vendors
2. Add new vendor submissions
3. Export comparison reports
4. Share findings with stakeholders

---

**Created for Charleston School of Law SIS Evaluation 2025**

*Industry Context: Most law schools of this size (650 students) can expect to invest $1M-1.5M over 5 years for a comprehensive SIS solution including implementation, training, and ongoing support.*