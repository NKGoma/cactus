# Love Slots - A Valentine's Game

A Frutakia-style slot machine game made with love.

## How to Play

1. Open `index.html` in your browser
2. Click **"Play My Love"** to start
3. Hit **Spin!** (or press spacebar) to spin the reels
4. Match symbols to win hearts (credits)
5. Win enough times to unlock new **universes**

## Adding Your Own Photos

Replace the default emoji symbols with your own pictures:

1. **Put your images** in the `images/` folder (jpg, png, gif all work)
2. **Open `index.html`** in a text editor
3. **Find this section** near the top of the `<script>` tag:

```javascript
const CUSTOM_IMAGES = [
    // Add your image filenames here! Place the files in the /images folder.
    // 'us-together.jpg',
    // 'our-pet.jpg',
    // ...
];
```

4. **Uncomment and replace** with your actual filenames:

```javascript
const CUSTOM_IMAGES = [
    'us-together.jpg',
    'our-pet.jpg',
    'favorite-place.jpg',
    'heart-photo.jpg',
    'special-moment.jpg',
    'your-smile.jpg',
];
```

You need at least **4 images** for the custom mode to activate.

## Universes

Unlock new themed worlds by winning:

| Universe | Wins Needed | Theme |
|----------|------------|-------|
| First Love | 0 | Pink & purple |
| Starlight Date | 5 | Deep blue & stars |
| Golden Paradise | 12 | Gold & warm |
| Rose Garden | 22 | Pink roses |
| Eternal Love | 35 | Purple & cosmic |

## Features

- Frutakia-style 3-reel slot machine
- Custom image support (replace fruits with your photos)
- 5 unlockable universe themes
- Basketball court background with floating basketballs
- Background music from YouTube
- Confetti and heart celebrations on wins
- Responsive design (works on mobile too)
- Spacebar to quick-spin
