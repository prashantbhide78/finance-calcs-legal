# 🚀 GitHub Pages Setup Instructions

## Step 1: Upload Files to Your Repository

1. **Navigate to your repository**: https://github.com/prashantbhide78/finance-calcs-legal

2. **Upload the HTML files**:
   - Click "Add file" → "Upload files"
   - Drag and drop these files:
     - `index.html`
     - `privacy.html`
     - `terms.html`
     - `README.md`

3. **Commit the files**:
   - Add commit message: "Add legal pages for Finance Calcs"
   - Click "Commit changes"

## Step 2: Enable GitHub Pages

1. **Go to Settings**:
   - In your repository, click the "Settings" tab

2. **Find Pages section**:
   - Scroll down to "Pages" in the left sidebar

3. **Configure Pages**:
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select "main" (or "master")
   - **Folder**: Select "/ (root)"
   - Click "Save"

4. **Wait for deployment**:
   - GitHub will show a green checkmark when ready
   - Usually takes 1-2 minutes

## Step 3: Your Live URLs

Once deployed, your pages will be available at:

- **Home**: https://prashantbhide78.github.io/finance-calcs-legal/
- **Privacy Policy**: https://prashantbhide78.github.io/finance-calcs-legal/privacy.html
- **Terms of Service**: https://prashantbhide78.github.io/finance-calcs-legal/terms.html

## Step 4: Update Your App

Update the URLs in your Finance Calcs app:

### In `app/about.tsx`:
```typescript
// Replace these lines:
onPress={() => openURL('https://financecalcs.app/privacy')}
onPress={() => openURL('https://financecalcs.app/terms')}

// With:
onPress={() => openURL('https://prashantbhide78.github.io/finance-calcs-legal/privacy.html')}
onPress={() => openURL('https://prashantbhide78.github.io/finance-calcs-legal/terms.html')}
```

## 🎯 Features of Your Legal Pages

### ✅ Professional Design
- Clean, mobile-responsive layout
- Consistent branding with Finance Calcs
- Easy navigation between pages

### ✅ Comprehensive Content
- **Privacy Policy**: Emphasizes your privacy-first approach
- **Terms of Service**: Clear disclaimers and limitations
- **Legal Protection**: Proper disclaimers for App Store compliance

### ✅ SEO & Accessibility
- Proper HTML structure
- Mobile-friendly responsive design
- Fast loading and professional appearance

## 🔄 Making Updates

To update your legal pages:

1. Edit the HTML files locally
2. Upload the updated files to GitHub
3. GitHub Pages will automatically update (takes 1-2 minutes)

## 🌐 Custom Domain (Optional)

Later, you can add a custom domain like `legal.financecalcs.com`:

1. Buy a domain
2. Add a `CNAME` file to your repository
3. Configure DNS settings
4. Update GitHub Pages settings

## ✅ Next Steps

1. Upload files to GitHub
2. Enable GitHub Pages
3. Test the live URLs
4. Update your app with the new URLs
5. Submit your app update

Your legal pages are now professional, compliant, and ready for the App Store! 🎉
