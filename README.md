Express.js Server with MongoDB and Socket.IO
=====================================================
Overview
This is a Node.js server built with Express.js, MongoDB, and Socket.IO. It provides a RESTful API for interacting with a MongoDB database and real-time updates using Socket.IO.
Features
RESTful API for CRUD operations on MongoDB collections
Real-time updates using Socket.IO
Support for multiple collections and databases
Connection string to specify from where to fetch
Error handling and logging
API Endpoints
Fetch Logs API
GET fetch-logscollectionName Fetch logs for a specific collection
Query Parameters
selectedDate Date for which logs are to be fetched
Dashboard Metrics API
GET dashboard-metricscollectionName Fetch dashboard metrics for a specific collection
Collection Operations
GET fetch-collectioncollectionName Fetch all documents in a collection
POST insert-documentcollectionName Insert a new document into a collection
PUT update-documentcollectionNameid Update a document in a collection
DELETE delete-documentcollectionNameid Delete a document from a collection
Other Endpoints
GET get-local-datacollectionName Get local data for a collection
POST save-filter-datacollectionName Save filtered data for a collection
POST save-filter-selectionscollectionName Save filter selections for a collection
GET load-filter-selectionscollectionName Load filter selections for a collection
POST save-dark-mode Save dark mode setting
GET load-dark-mode Load dark mode setting
POST set-alert Set an alert
Setup and Installation
Clone the repository git clone https://github.com/fasinabsons/Arabian-Live.git
Install dependencies npm install
Start the server node server.js
Contributing
Contributions are welcome! Please submit a pull request with your changes.
License
This project is licensed under the GNU License. See LICENSE for details.
