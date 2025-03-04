Express.js Server with MongoDB and Socket.IO
=====================================================
##Overview
### This is a Node.js server built with Express.js, MongoDB, and Socket.IO. It provides a RESTful API for interacting with a MongoDB database and real-time updates using Socket.IO.
Features
---
### RESTful API for CRUD operations on MongoDB collections
### Real-time updates using Socket.IO
### Support for multiple collections and databases
### Error handling and logging
---
## API Endpoints
### Fetch Logs API
### GET /fetch-logs/:collectionName: Fetch logs for a specific collection
---
## Query Parameters:
### selectedDate: Date for which logs are to be fetched
---
## Dashboard Metrics API
### GET /dashboard-metrics/:collectionName: Fetch dashboard metrics for a specific collection
## Collection Operations
### GET /fetch-collection/:collectionName: Fetch all documents in a collection
### POST /insert-document/:collectionName: Insert a new document into a collection
### PUT /update-document/:collectionName/:id: Update a document in a collection
### DELETE /delete-document/:collectionName/:id: Delete a document from a collection
---
##Other Endpoints
### GET /get-local-data/:collectionName: Get local data for a collection
### POST /save-filter-data/:collectionName: Save filtered data for a collection
### POST /save-filter-selections/:collectionName: Save filter selections for a collection
### GET /load-filter-selections/:collectionName: Load filter selections for a collection
### POST /save-dark-mode: Save dark mode setting
### GET /load-dark-mode: Load dark mode setting
### POST /set-alert: Set an alert
---

## Setup and Installation
### Clone the repository: git clone https://github.com/fasinabsons/Arabian-Live.git
### Install dependencies: npm install
### Start the server: node server.js
---

# MEAN Stack Angular Frontend

## Welcome!
This Angular frontend is the face of a powerful MEAN stack application designed to make working with data simple, enjoyable, and efficient. Whether you're searching through collections, visualizing trends, or downloading reports, this app has you covered with a clean and intuitive interface. It’s built to adapt to your needs, look great, and feel seamless—perfect for anyone who wants to dive into their data without the headache.

---

## What You Can Do

### Search and Explore Your Data
- Easily look through all kinds of data—like sales, purchases, or forecasts—and see it laid out in a way that’s easy to understand.
- Choose how you want to view it: tables, cards, or whatever fits the moment.

### Download What You Need
- Grab your data as an Excel or CSV file with just a click. Take only what you want for offline use—it’s that simple.

### Pick Up Where You Left Off
- Your favorite filters (like dates or specific logs) stick around, so you don’t have to start over every time you log in. Less work, more flow.

### See the Future with Graphs
- Check out forecasts with colorful charts—bars, lines, or pie slices—that you can tweak to your liking.
- Switch between monthly, quarterly, or yearly views to spot trends your way.

### Make the Dashboard Yours
- Get a quick snapshot of what matters most, like recent updates or live activity, all on a dashboard you can customize.
- Move things around, pick your widgets, and make it feel like home.

### Stay in the Loop
- **Approval Logs**: See what’s been created or changed lately.
- **Live Logs**: Watch updates as they happen, keeping everything transparent and easy to follow.
- Filter them however you like—by user, date, or type.

### Work Smarter, Not Harder
- The app keeps things fast and light, so you’re not waiting around. Real-time updates pop in smoothly without slowing anything down.

### Dark Mode for Night Owls
- Flip on dark mode for a sleek, eye-friendly look whenever you’re burning the midnight oil.

---

## How to Get Started

### What You’ll Need
- A computer with Node.js and npm (don’t worry, they’re easy to install!).
- The backend part of this app up and running (your tech team can help with that).

### Quick Setup
1. **Get the Code**: Download it from our repository.
2. **Set It Up**: Open a terminal, go to the project folder, and type `npm install`.
3. **Launch It**: Run `ng serve`, then visit `http://localhost:4200` in your browser.
4. **Connect the Backend**: Make sure the backend is on (probably at `http://localhost:3000`).

That’s it—you’re ready to roll!

---

## Want to Help Out?
We’d love your input! If you’ve got ideas or fixes:
1. Grab a copy of the project.
2. Make your changes in a new branch.
3. Send them our way with a quick note about what you did.

---

## License
This app is free to use, tweak, and share under the **GNU General Public License (GPL)**. Just follow its rules, and you’re good to go.

---

## Good to Know

### It’s Fast and Friendly
- Handles big piles of data without breaking a sweat, keeping things smooth with clever tricks like loading only what’s needed.
- Works great for everyone, with easy navigation and a design that’s accessible to all.

### What’s Next?
- More filter options to dig deeper into your data.
- Login features to keep things secure.
- A better fit for your phone or tablet.
- Smarter tools to predict trends and analyze insights.

---

## Let’s Chat
Got questions or ideas? Reach out to us at `findit569@gmail.com`. We’d love to hear from you!

---

Thanks for checking out this Angular frontend! We hope it makes your data adventures easier and more fun. Enjoy!
