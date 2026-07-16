mkdir -p ~/maru-tako-website/product-photos
cd ~/Desktop
cp index.html "訂購系統.html" maru-tako-logo.png maru-tako-logo-favicon.png hero-banner.jpg ~/maru-tako-website/
cp product-photos/*.png ~/maru-tako-website/product-photos/
cd ~/maru-tako-website
git init
git add .
git commit -m "Initial commit: Maru Tako website"
git branch -M main
git remote add origin YOUR-REPO-URL
git push -u origin main
