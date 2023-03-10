# npm
npm install npm -g
const fs = require('fs');

fs.readFile('file.txt', 'utf8', (err, data) => {
  if (err) {
    console.error(`Failed to read file: ${err}`);
    return;
  }
  console.log(`File contents: ${data}`);
});
e
