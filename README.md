# The Scribbled NIGHTMARE – Creepy Drawings Gallery

Enter the nightmare. A fully interactive web gallery showcasing a collection of original creepy drawings. Toggle between the raw, scribbled versions and their realistic reinterpretations. Filter, search, favorite, and immerse yourself in a spooky, atmospheric experience.

Live Demo: https://instai4.github.io/Scribbled-NIGHTMARE/


Images: The gallery uses local image files – ensure the folders `./img/` and `./rimg/` are present with the correct images (named `1.jpg`, `2.png`, etc. as per the code).

---

## Features

### Dual View Modes
Switch between Creepy Mode (original scribbles) and Realistic Mode (rendered versions) with a single click.

### Dynamic Filtering
Browse all drawings or filter by categories:
- Monsters  
- Ghosts  
- Creatures  
- Abstract Horror  

### Search
Find drawings by title, description, or tags.

### Favorites
Save your favorite drawings to local storage. Favorites persist even after you close the browser.

### Full-Screen Modal
Click any drawing to view it in a larger format. Navigate using arrow keys, download images, share using the Web Share API, and toggle favorites directly from the modal.

### Shuffle
Randomize the gallery order for a new experience every time.

### Atmospheric Design
Includes cobweb effects, blood splatters, candle flicker animations, and a themed loading screen.

### Fully Responsive
Optimized for desktop, tablet, and mobile devices.

---

## Built With

- HTML5 – Semantic structure  
- CSS3 – Custom properties (variables), animations, grid, flexbox  
- JavaScript (ES6) – Dynamic rendering, local storage, event handling  
- Font Awesome 6 – Icons  
- Google Fonts – Creepster and Special Elite  

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- Image folders:
  - `./img/` (creepy versions)
  - `./rimg/` (realistic versions)

Each folder must contain the correctly numbered images (`1.jpg`, `2.png`, etc.) matching the filenames used in the `drawingsData` array inside the JavaScript code.

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/instai4/creepy-drawings-gallery.git
