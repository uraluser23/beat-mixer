# Beat Mixer — Download & Run Instructions

## Quick Start (2 minutes)

### Option 1: Netlify Drop (easiest, no account needed)
1. Go to https://app.netlify.com/drop
2. Drag the entire `beat-mixer-site` folder onto the page
3. Your mixer is live in seconds — you get a public URL

### Option 2: Run locally
1. Install Node.js (nodejs.org) if you don't have it
2. In the folder, run: `npx serve .`
3. Open http://localhost:3000

### Option 3: GitHub Pages
1. Create a new GitHub repository
2. Drag these files into it (or git push)
3. Go to Settings → Pages → Deploy from branch → main
4. Your mixer is live at https://USERNAME.github.io/REPONAME

## Using the Mixer

### Add Samples
- **Demo Samples** — click "Load Demo Samples" for 5 built-in sounds (kick, snare, hi-hat, clap, bass)
- **Upload** — click "Upload WAV/MP3" to load your own files (any audio format)
- **Freesound** — click "Freesound Browser", paste your API key (free from freesound.org/apiv2/apply), search and add

### Freesound API Key
1. Register free at https://freesound.org
2. Go to https://freesound.org/apiv2/apply
3. Create a credential → copy the "Client secret/API key"
4. Paste it into the "Freesound API Key" field in the app

### Controls Per Track
- **Volume** — how loud that track is in the mix
- **Pan** — L=left speaker, C=center, R=right speaker
- **FX button** — opens the Effects Rack for that track:
  - **EQ Bass/Mid/Treble** — boost or cut frequencies (-12 to +12 dB)
  - **Reverb** — adds room/hall echo (0% = dry, 100% = soaking wet)
  - **Compressor** — squashes loud peaks for a tighter sound

### Export
Click **"Export WAV"** — the app renders your full mix offline (faster than real-time) and downloads a 44.1 kHz stereo WAV file.
