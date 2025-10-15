// This is a simple Node.js script for a SillyTavern extension.
// It creates a basic server to provide the HTML file.
// You do not need to edit this file.

const express = require('express');
const app = express();
const port = 3000; // The internal port for the extension

// Serve static files from the 'public' folder
app.use(express.static('public'));

app.listen(port, () => {
  console.log(`[Fantasy Journal] Extension server running.`);
});

// This is required by SillyTavern to know the extension is running.
process.send('ready');
