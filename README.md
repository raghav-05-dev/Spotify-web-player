# 🎵 Spotify Web Player Clone

A modern, responsive Spotify-inspired web music player built using **HTML, CSS, and JavaScript**. This project recreates the core experience of Spotify's web player, allowing users to browse albums, load songs dynamically, and control music playback directly from the browser.

---

## 🚀 Features

### 🎶 Music Playback
- Play songs directly in the browser
- Pause and resume playback
- Real-time song progress tracking
- Automatic song information display

### ⏮️ Playback Controls
- Previous track navigation
- Play/Pause toggle
- Next track navigation
- Seamless track switching

### 📀 Dynamic Album Library
- Album-based music organization
- Dynamic song loading from folders
- Clickable album cards
- Playlist updates without page refresh

### 🎚️ Interactive Seek Bar
- Displays current playback position
- Click anywhere on the seek bar to jump to a specific timestamp
- Live progress updates while the song is playing

### 🔊 Volume Control
- Adjustable volume slider
- Instant volume updates

### 📱 Responsive Design
- Fully responsive layout
- Mobile-friendly sidebar navigation
- Hamburger menu for smaller screens
- Adaptive album grid layout

### 🎨 Modern Spotify-Inspired UI
- Dark theme design
- Smooth hover effects
- Custom scrollbar styling
- Clean and intuitive interface

---

## 🛠️ Built With

- **HTML5** – Structure and content
- **CSS3** – Styling and responsiveness
- **JavaScript (ES6+)** – Functionality and interactivity
- **Fetch API** – Dynamic song loading
- **HTML Audio API** – Music playback and controls

---

## Screenshots

<img width="1920" height="1080" alt="Home screen" src="https://github.com/user-attachments/assets/210aa884-6dd1-4610-81b5-d25057cd5c6c" />
<img width="1920" height="1080" alt="Song playing from your library" src="https://github.com/user-attachments/assets/5087f020-37a7-49ce-b161-81ed2eff8b6f" />
<img width="1387" height="150" alt="playbar and controls" src="https://github.com/user-attachments/assets/09f4d141-f540-484e-9520-260cf74b3e36" />
<img width="493" height="913" alt="Your library section" src="https://github.com/user-attachments/assets/b443227f-1b47-4a85-8462-20aa809635d3" />
<img width="1920" height="1080" alt="library changes according to the album" src="https://github.com/user-attachments/assets/d21ddd94-d6e4-42d9-8fdf-3748fa37c306" />
<img width="1920" height="1080" alt="responsive design" src="https://github.com/user-attachments/assets/871ecf46-9903-4d83-9cc6-8ccfa5dcf407" />
<img width="1920" height="1080" alt="website on a tablet" src="https://github.com/user-attachments/assets/09797b58-07a9-4a56-86cd-edde62dc11e6" />
<img width="1920" height="1080" alt="hamburger section on tablet" src="https://github.com/user-attachments/assets/060931cc-ea3d-4e85-b951-26d8325eaeb3" />
<img width="1920" height="1080" alt="website on phone" src="https://github.com/user-attachments/assets/eca30c42-e29a-46b3-ac5c-c16fc6f1175f" />
<img width="1920" height="1080" alt="hamburger section on phone" src="https://github.com/user-attachments/assets/aa2e5dee-a624-4d47-966a-85922c46125e" />

---

## 📂 Project Structure

```text
spotify-web-player/
│
├── index.html
├── script.js
├── style.css
├── utility.css
│
├── songs/
│   ├── album1/
│   │   ├── song1.mp3
│   │   ├── song2.mp3
│   │   └── ...
│   │
│   ├── album2/
│   └── album3/
└── README.md
```

---

## ⚡ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/spotify-web-player.git
```

### 2. Open the Project Folder

```bash
cd spotify-web-player
```

### 3. Run a Local Server

Since the project uses the Fetch API, it must be served from a local server.

#### Using VS Code Live Server

```text
Right Click → Open with Live Server
```

#### Using Python

```bash
python -m http.server 3000
```

### 4. Open in Browser

```text
http://localhost:3000
```

---

## 🎵 How It Works

### Dynamic Song Loading

The application scans music folders and automatically generates playlists based on available `.mp3` files.

### Album Selection

Clicking an album card loads all songs associated with that album and updates the playlist instantly.

### Audio Management

A single audio instance handles:

- Playback
- Pause/Resume
- Seeking
- Volume Control
- Previous/Next Navigation

### Responsive Navigation

On mobile devices:

- The sidebar becomes collapsible
- A hamburger menu appears
- Navigation remains accessible without affecting playback

---

## 📱 Responsive Support

| Device Type | Supported |
|------------|-----------|
| Desktop    |     ✅   |
| Laptop     |     ✅   |
| Tablet     |     ✅   |
| Mobile     |     ✅   |

---

## ✨ Highlights

- Dynamic playlist generation
- Album-based music browsing
- Real-time progress tracking
- Interactive seek bar
- Volume control
- Previous/Next navigation
- Responsive sidebar
- Mobile-friendly UI
- Spotify-inspired design
- Lightweight and fast

---

## 🔮 Future Improvements

- Search functionality
- Shuffle mode
- Repeat mode
- Playlist creation
- Favorite songs
- Recently played section
- User authentication
- Backend integration
- Spotify API integration
- Music metadata support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

🎯 Learning Outcomes

Through this project, I learned:

1. Responsive web design principles
2. DOM manipulation using JavaScript
3. Audio handling in JavaScript
4. Event listeners and user interactions
5. Project structuring and code organization
6. Version control with Git and GitHub

---

## 📄 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author
Raghav Pandey
Developed as a Spotify Web Player Clone using HTML, CSS, and JavaScript to demonstrate:

- Responsive Web Design
- DOM Manipulation
- JavaScript Event Handling
- Audio Playback Management
- Dynamic Content Rendering
- Frontend Development Best Practices

---

⭐ If you found this project useful, consider giving it a star on GitHub!
