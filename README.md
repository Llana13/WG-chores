# Flatmate Chore Tracker

A simple, interactive web app to help flatmates organize and track household chores on a weekly rotation basis.

---

## Features

- **Weekly chore schedule** for 4 flatmates and 4 chores.
- **Automatic rotation** of chores each week based on the current week of the year.
- **Mark chores as completed** with checkboxes for the current week.
- **Monthly themes** with motivational descriptions and a button to generate a new theme.
- **Chore history** showing completed chores with dates.
- **Responsive design** optimized for desktop and mobile devices.
- **Reset and rotate controls** to start fresh or move to the next week.

---

## How to Use

1. Open the `index.html` file in any modern web browser.
2. View the chore schedule for the current month and week.
3. Tick the checkboxes next to chores when completed (only available for the current week).
4. Use the **Rotate to Next Week** button to move the schedule forward.
5. Use the **Generate Schedule** button to refresh the schedule.
6. Use the **Reset All** button to clear all completed chores and history.
7. Click **Generate New Theme** to cycle through monthly motivational themes.

---

## Technical Details

- Built with **HTML**, **CSS**, and **JavaScript** in a single file.
- Uses JavaScript to dynamically generate schedules and track state.
- Responsive layout using CSS Grid and Flexbox.
- No backend or database - all data is stored **locally in memory** during the session.
- Does **not** persist data between page reloads or across devices.

---

## Limitations

- **No data synchronization:** Changes (e.g., checked chores) are only visible on the device where they are made.
- **No persistent storage:** Refreshing the page resets all completed chores and history.
- Designed for **up to 4 flatmates and 4 chores**; requires code changes to scale.
- No user authentication or multi-user support.

---

## Future Improvements

- Add persistent storage with **localStorage** or a backend database.
- Enable real-time synchronization across devices (e.g., using Firebase).
- Allow dynamic addition/removal of flatmates and chores.
- Add user authentication for personalized tracking.
- Enhance UI/UX with animations and notifications.

---

## Deployment

- The app can be hosted as a **static website** on platforms like **GitHub Pages**, **Netlify**, or **Firebase Hosting**.
- Simply upload the `index.html` file to the hosting service.
- No server-side code required.

---

## License

This project is open source and free to use.

---

*Feel free to contribute or open issues if you want to suggest improvements!*
