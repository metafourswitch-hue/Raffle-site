PC Raffle Netlify Site

Files:
- index.html
- pc-placeholder.svg

How to customize:
1. Replace pc-placeholder.svg with a real PC image.
   - Name your photo something simple like pc.jpg.
   - Then in index.html, change:
     <img src="pc-placeholder.svg" alt="Raffle PC" />
   - To:
     <img src="pc.jpg" alt="Raffle PC" />

2. Change the stream link.
   Search in index.html for:
   https://example.com/your-stream-link
   Replace it with your YouTube, Twitch, or livestream URL.

3. Change the specs.
   Search for "PC Specs" in index.html and edit the CPU, graphics, RAM, storage, etc.

How to put it on Netlify:
1. Go to Netlify.
2. Add new site.
3. Choose "Deploy manually" or drag-and-drop deploy.
4. Drag the whole folder onto Netlify.
5. Netlify will give you a URL like:
   something.netlify.app

Important:
The homepage file must be named index.html.
