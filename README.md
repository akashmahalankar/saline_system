# Saline System Dashboard

An impressive, real-time dashboard for monitoring patient saline levels in a hospital, built with Tailwind CSS and Alpine.js. The dashboard displays patient statistics floor-wise, provides instant alerts when saline levels drop below a threshold, and offers a dynamic, responsive UI for easy monitoring.

## Features

- **Floor-wise Patient Monitoring:** Sidebar navigation to select hospital floors and view all patients on that floor.
- **Patient Cards:** Each patient is displayed in a visually appealing card showing their name, bed number, and current saline level.
- **Real-Time Alerts:** Automatic alert indicator when a patient's saline level drops below the safe threshold.
- **Responsive Design:** Dashboard scales beautifully across devices and screen sizes.
- **Easy Customization:** Built with Tailwind CSS for rapid UI changes and Alpine.js for simple interactivity.
- **Demo Data:** Includes mock patient data for demonstration and testing purposes.

## Getting Started

1. **Clone the repository:**
   ```powershell
   git clone https://github.com/akashmahalankar/saline_system.git
   ```
2. **Open the project in VS Code.**
3. **Open `saline_system/dashboard.html` in your browser.**
   - No build step required; all dependencies are loaded via CDN.

## Project Structure

```
saline_system/
  dashboard.html   # Main dashboard UI
  ...              # Other supporting files
```

## Customization
- To add or modify patient data, edit the `patients` array in the `<script>` section of `dashboard.html`.
- To change floor numbers, update the sidebar button list.

## Technologies Used
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Alpine.js](https://alpinejs.dev/) for interactivity




---
**Created by Akash Mahalankar**
