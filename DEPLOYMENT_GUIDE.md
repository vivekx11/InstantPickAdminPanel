# 🚀 GitHub Pages Deployment Guide

## Step-by-Step Instructions

### 1. Enable GitHub Pages

1. Go to your repository: https://github.com/vivekx11/InstantPickAdminPanel
2. Click on **Settings** (top right)
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### 2. Wait for Deployment

- GitHub will automatically deploy your site
- Wait 2-3 minutes for the first deployment
- You'll see a green checkmark when ready

### 3. Access Your Admin Panel

Your admin panel will be live at:
```
https://vivekx11.github.io/InstantPickAdminPanel/
```

### 4. Login Credentials

```
Username: admin
Password: InstantPick@2024
```

## 🔄 Updating the Admin Panel

When you want to update the admin panel:

```bash
# Navigate to the folder
cd admin_panel_deploy

# Make your changes to index.html

# Commit and push
git add .
git commit -m "Update admin panel"
git push origin main
```

GitHub Pages will automatically redeploy within 1-2 minutes.

## ✅ Verification

After deployment, verify:
- [ ] Site loads correctly
- [ ] Login works
- [ ] All sections are accessible
- [ ] API calls work
- [ ] Responsive design works on mobile

## 🔒 Security Notes

- Keep your admin credentials secure
- Don't share the admin panel URL publicly
- Consider adding IP restrictions if needed
- Monitor access logs regularly

## 📱 Custom Domain (Optional)

If you want to use a custom domain:

1. Go to Settings → Pages
2. Add your custom domain
3. Update DNS records at your domain provider
4. Enable HTTPS

## 🆘 Troubleshooting

**Site not loading?**
- Check if GitHub Pages is enabled
- Verify the branch is set to `main`
- Wait a few minutes for deployment

**404 Error?**
- Make sure `index.html` is in the root folder
- Check repository visibility (should be public)

**Login not working?**
- Clear browser cache
- Check browser console for errors
- Verify API endpoint is accessible

## 📞 Support

For issues, check:
- GitHub Pages status
- Browser console errors
- Network tab for API calls

---

**Deployed Successfully!** 🎉
Your admin panel is now live on GitHub Pages!
