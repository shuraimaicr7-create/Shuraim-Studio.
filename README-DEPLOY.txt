SHURAIM STUDIO - GO LIVE + GOOGLE SEARCH CONSOLE

1. Replace the placeholder domain everywhere (index.html, robots.txt, sitemap.xml):
   sed -i 's#https://YOUR-DOMAIN.com#https://yourrealdomain.com#g' index.html robots.txt sitemap.xml

2. Upload ALL files to the site root (Cloudflare Pages, Netlify, Vercel, GitHub Pages, or any host).
   Check these open in a browser:
   /robots.txt  /sitemap.xml  /site.webmanifest  /og-image.png

3. Google Search Console (search.google.com/search-console):
   - Add property -> "Domain" (DNS TXT record) or "URL prefix" (upload HTML file / meta tag / DNS).
   - Sitemaps -> enter sitemap.xml -> Submit.
   - URL Inspection -> paste your homepage URL -> "Request indexing".
   Indexing usually takes a few days to a couple of weeks.

4. Optional: Bing Webmaster Tools -> import from Search Console.
