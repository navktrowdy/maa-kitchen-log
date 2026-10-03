# Maa Madurai Kitchen Log

Staff website for the morning veg check and the closing food balance.
Entries are saved to the owner's Google Sheet through a Google Apps Script
web app (link in `config.js`); this repository holds no data.

The source, the Apps Script code and the tests live in the private
`maa_operations` repository under `kitchen-log/`. Change them there, run
`node kitchen-log/test/e2e.mjs`, then copy `site/index.html` and
`site/config.js` here.
