NICOLE BULLOCK - HOMEPAGE DEPLOYMENT

This build uses cropped pixels from the user-supplied Instagram screenshots, NOT generated portraits. Higher-resolution approved originals should replace public/nicole-green-original.jpg and public/nicole-speaking-original.jpg later.

The sermon player uses the exact YouTube video ID supplied by the user: 3rsyp--c3O4. Playback requires YouTube embedding to be allowed by the video's owner.

The website is not yet deployed by ChatGPT. To deploy:
1. Unzip this archive.
2. Copy all files and folders from inside nicole-live into ~/Desktop/nicole-bullock-website (replace existing files).
3. In Terminal run:
cd ~/Desktop/nicole-bullock-website && npm install && npm run build && firebase deploy --only hosting

Check https://nicole-bullock-website.web.app after deployment.

Some navigation sections are homepage anchors, and coaching/booking calls to action temporarily route to Nicole's Instagram until approved contact details and forms are supplied.
