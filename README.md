# quarantine-buster
Get your org emails past Cisco's cancerous piece of software

## Set Up
 - Clone the repo, make sure you have Node installed and `npm install`, you know the drill.
 - Copy `config-sample.json` to `config.json` and enter you credentials. This is set up for using Office 365, I don't know what anything else will look like.
 - Add a template HTML file.
 - Update `index.js` so that all your info is replaced as you see fit (line 33). You're prob a CS major so I trust that you can do that.

## Usage
  - `node index.js ./path_to.csv ./path_to_template.html`
