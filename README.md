# React Timetable App

A simple timetable app built with React to display class schedules for each day of the week, highlighting the current ongoing class based on the system time.

## Features

- Displays class schedule for each day of the week.
- Highlights the ongoing class in green.
- Allows switching between days.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-timetable-app.git
   cd react-timetable-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Add a `data.json` file in the `public` folder with your timetable data:
   ```json
   {
     "timetable": {
       "Monday": [
         { "name": "Android", "startTime": "09:30", "endTime": "10:30", "type": "Lab" }
       ],
       // Add other days
     }
   }
   ```

4. Start the app:
   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- **`App.js`**: Main component that fetches and displays the timetable for the current day.
- **`Box.js`**: Renders each class session, highlights the current session.

## Customization

- **Timetable Data**: Update `data.json` in the `public` folder.
- **Styling**: Modify `App.css` for styling changes.

## License

MIT License

---

Enjoy your React Timetable App!
