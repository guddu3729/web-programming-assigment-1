# Random Group — Web Programming Profile

## Overview
- Single-page group profile: `guddu.html`
- Members: Lakshani Fernando, Shubham Raj, Agampodige Randika Dilshan Rajapaksha, Guddu Kumar
- Includes biographies, hobbies, education, work experience, photos, YouTube videos, local media, map, and contact details

## Open Locally
- Double-click `guddu.html` or open it in a browser

## Media & Images
- Place local media in `media/`
  - `media/lakshani_intro.mp4`, `media/lakshani_voice.mp3`
  - `media/shubham_intro.mp4`, `media/shubham_voice.mp3`
  - `media/randika_intro.mp4`, `media/randika_voice.mp3`
  - `media/guddu_intro.mp4`, `media/guddu_voice.mp3`
- Images used in the root folder
  - `Lakshani.jpg`, `Shubham.png`, `Dilshan Rajapaksha.jpg`, `Guddu.png`

## Update Content
- Edit text inside each member section in `guddu.html`
- Replace YouTube links in each `iframe` with your own if needed
- Update the map by changing the `iframe src` in the Contact section

## Publish to GitHub Pages
- Initialize and push
  - `git init`
  - `git add guddu.html README.md Lakshani.jpg Shubham.png "Dilshan Rajapaksha.jpg" Guddu.png`
  - If you add media: `git add media`
  - `git commit -m "Random Group profile page"`
  - `git branch -M main`
  - `git remote add origin https://github.com/<username>/<repo>.git`
  - `git push -u origin main`
- Enable Pages
  - GitHub → `Settings` → `Pages`
  - Source: `Deploy from a branch`
  - Branch: `main`, Folder: `/root`
- URL
  - `https://<username>.github.io/<repo>/guddu.html`

## Submission
- Zip the project folder including `guddu.html`, images, and media
- Submit the zip file and the GitHub Pages URL
