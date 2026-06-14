# Apex

Apex is a cinematic streaming discovery platform that combines live movie and TV data with AI-powered recommendations.

Built with a custom amber-gold aesthetic, Apex helps users discover films and series through intelligent search, curated collections, and an immersive browsing experience.

---

## Features

### 🎬 Content Discovery

Apex pulls live content directly from The Movie Database (TMDB), providing:

* Movie and TV posters
* Backdrop images
* Ratings
* Genres
* Overviews
* Trending content

The Home page includes multiple curated content rows:

* Trending
* Popular Movies
* Popular TV Shows
* Top Rated
* Upcoming Releases
* Action Collection

Additional sections include:

* Home
* Movies
* TV Shows
* Trending

Each section contains its own curated content experience.

---

### ✦ AI Search

Apex includes an AI-powered search experience powered by Claude.

Users can search naturally using prompts such as:

* "Psychological thrillers like Black Swan"
* "Feel-good sitcoms from the 90s"
* "Dark sci-fi movies with mind-bending plots"

The AI:

1. Extracts user intent
2. Determines the most relevant TMDB searches
3. Retrieves matching content
4. Explains why recommendations were selected

AI results appear instantly above the standard content rows.

---

### 🎥 Streaming Player

Apex integrates with Vidking to provide movie and TV playback.

Features include:

* Movie streaming
* Full TV series support
* Season selection
* Episode navigation
* Instant episode switching
* Keyboard shortcuts
* One-click exit controls

---

### 🎨 User Experience

Designed to feel cinematic rather than imitate existing streaming platforms.

Highlights:

* Amber-gold accent system
* Pure black visual theme
* Dynamic ambient backdrops
* Smooth hover animations
* Skeleton loading states
* Poster-optimized layouts
* Responsive design

When hovering over content, the page background dynamically adapts to the selected title's backdrop image.

---

## Technology Stack

* HTML
* CSS
* JavaScript
* TMDB API
* Anthropic Claude API
* Vidking Embed Integration

---

## Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/apex.git
cd apex
```

### 2. Open Application

No installation or server is required.

Simply open:

```text
index.html
```

in any modern browser.

---

## API Configuration

Apex requires:

* TMDB API Key
* Anthropic API Key (optional for AI Search)

Insert your keys into the configuration section of the application.

---

## Notes

The AI search feature calls the Anthropic API directly from the browser.

Depending on browser settings, CORS restrictions may prevent requests from executing locally.

If AI search is unavailable:

* Standard TMDB search remains fully functional
* Content browsing and streaming features continue to work normally

---

## Disclaimer

Apex is intended for educational and demonstration purposes.

Users are responsible for complying with all applicable copyright laws, streaming regulations, and third-party service terms.
