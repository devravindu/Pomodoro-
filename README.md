# 🍅 Pomodoro Timer Web App

A clean, modern, and responsive Pomodoro Timer web application built with vanilla JavaScript, HTML, and Tailwind CSS. This tool helps users manage their work and break sessions using the Pomodoro Technique, boosting productivity and focus.

![Pomodoro Timer Screenshot](https://i.ibb.co/Y7TGjX1N/Screenshot-2025-06-20-201338.png)
*(Suggestion: Replace the placeholder above with a screenshot or GIF of the running application)*

---

## 📘 Table of Contents

- [Live Demo](#-live-demo)
- [✨ Core Features](#-core-features)
- [🔧 Technology Stack](#-technology-stack)
- [🚀 Getting Started](#-getting-started)
- [▶️ How to Use](#️-how-to-use)
- [⚙️ Configuration](#️-configuration)
- [📈 Future Enhancements](#-future-enhancements)
- [📄 License](#-license)

---

## 🌐 Live Demo

*(Suggestion: Once deployed, add a link to the live application here.)*
**[Link to your live app]**

---

## ✨ Core Features

-   **Pomodoro, Short, & Long Break Timers**: Standard 25-minute work sessions with 5-minute short breaks and 15-minute long breaks.
-   **Customizable Durations**: Easily adjust the length of each session (Pomodoro, Short Break, Long Break) and the long break interval via a settings modal.
-   **Audio Alerts**: A subtle browser-generated sound notifies you when a session ends. No external audio files needed.
-   **Session Tracking**: Visually track your completed Pomodoro sessions for each long break cycle.
-   **Persistent Settings**: Your custom durations and completed session count are saved in the browser's `localStorage`.
-   **Responsive Design**: A beautiful and functional UI that works seamlessly on both desktop and mobile devices.
-   **Dark/Light Mode**: Toggle between light and dark themes, with the preference saved for your next visit.
-   **Start, Pause, & Reset**: Full control over the timer.

---

## 🔧 Technology Stack

-   **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/) for a utility-first styling approach.
-   **Audio**: [Tone.js](https://tonejs.github.io/) for generating audio alerts directly in the browser.
-   **Icons**: [Phosphor Icons](https://phosphoricons.com/) for clean and modern UI icons.
-   **Fonts**: [Google Fonts](https://fonts.google.com/) (Inter and Roboto Mono).

---

## 🚀 Getting Started

This project is a single, self-contained `index.html` file with no build step required.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/pomodoro-app.git](https://github.com/your-username/pomodoro-app.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd pomodoro-app
    ```

3.  **Run the application:**
    Simply open the `index.html` file in your favorite web browser.
    -   On macOS: `open index.html`
    -   On Windows: `start index.html`
    -   On Linux: `xdg-open index.html`

---

## ▶️ How to Use

1.  **Select a Mode**: Click on "Pomodoro", "Short Break", or "Long Break" to select the timer mode.
2.  **Start the Timer**: Click the **Start** button to begin the countdown.
3.  **Pause/Resume**: The "Start" button will become a **Pause** button. Click it to pause the timer and again to resume.
4.  **Reset**: Click the circular arrow button to reset the current timer to its initial duration.
5.  **Automatic Flow**: When a Pomodoro timer finishes, a break timer will start automatically, and vice-versa. After a set number of Pomodoros (4 by default), a long break is triggered.

---

## ⚙️ Configuration

You can customize the timer settings by clicking the **gear icon** in the top right corner.

-   **Timer Durations**: Set the time in minutes for each type of session.
-   **Long Break Interval**: Set how many Pomodoro sessions to complete before a long break starts.

All changes are saved automatically to your browser's local storage and will be applied the next time you visit.

---

## 📈 Future Enhancements

Based on the initial project specification, potential features to add include:

-   [ ] User login and persistent cross-device stats.
-   [ ] A daily Pomodoro goal tracker.
-   [ ] An analytics dashboard to view productivity trends.
-   [ ] PWA (Progressive Web App) support for offline usage.
-   [ ] Customizable sound/music options.
-   [ ] Voice notifications.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

