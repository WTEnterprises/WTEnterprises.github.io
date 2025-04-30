
## Setup Instructions

### 1. Amazon Associates Configuration
1. Replace all instances of `yourtrackingid-20` with your actual Amazon Associates tracking ID
2. Replace `yourlinkid` with your Amazon link ID
3. Update example ASINs (e.g., `B08N5KWB9H`) with products you want to promote

### 2. Ad Units Configuration
#### Banners (Native Shopping Ads)
1. In Amazon Associates dashboard:
   - Go to "Product Linking" > "Native Shopping Ads"
2. Configure your ad unit and copy the code
3. Replace the script in the `#amazon-banner` div

#### Product Widgets
1. In Amazon Associates dashboard:
   - Go to "Product Linking" > "Product Links"
2. Search for products and generate iframe code
3. Replace the iframes in the `.product-widget` divs

#### Text Links
1. Use the "Get Link" button on any product page
2. Add your links to the `#amazon-links` section

### 3. Customization Options
- **Colors**: Modify the CSS variables at the top of the style section
- **Categories**: Update the navigation menu items
- **Layout**: Adjust the grid in `.product-grid`

### 4. Amazon Compliance
- Keep the disclaimer in the footer
- Do not modify Amazon's ad code except for placement
- Ensure all links properly include your tracking ID

## Deployment
1. **Free Hosting**:
   - Upload to GitHub Pages by creating a repository named `username.github.io`
2. **Paid Hosting**:
   - Upload via FTP or file manager to your web host

## Troubleshooting
- **Ads not showing**: Verify your tracking ID is correct
- **Layout issues**: Check console for errors (F12 in browser)
- **Mobile problems**: Test with Chrome DevTools device mode

## Support
For Amazon Associates questions:  
[Amazon Associates Help](https://affiliate-program.amazon.com/help)

For code questions:  
Open an issue in this repository
