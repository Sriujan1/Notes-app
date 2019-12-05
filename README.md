# Notes-app

This is a notes app for storing notes using command line arguments. The app has been written in js.

# Build Setup

#install package.json
npm init

#install dependencies
npm install

# Commands to be used

#add notes =>
node app.js add --title='Your_title' --body='Description of the note'

#remove notes =>
node app.js remove --title='Your_title'

#list notes =>
node app.js list

#read note =>
node app.js --title='Your_title'
