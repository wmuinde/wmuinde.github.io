POTATO TRUCK MANAGER - SALES SITE: HOW TO GO LIVE
==================================================

WHAT IS IN THIS FOLDER
  index.html    the sales page (what buyers see)
  config.js     THE ONLY FILE YOU EDIT - 3 values
  admin.html    your private buyers log (never link it on the page)
  icon.png      app icon
  shots/        the 7 app screenshots shown on the page

STEP 1 - FILL config.js
  Open config.js in any text editor and fill:
    paybill       your Paybill or Till number (write "Till number" in
                  paybillLabel if you use a till)
    downloadLink  the direct link to PotatoTruckManager.apk
    whatsapp      your number, digits only with country code: 254700640607
  Save. That is the whole setup.

STEP 2 - HOST THE APK (so you have a downloadLink)
  Easiest: create a free GitHub repo, upload PotatoTruckManager.apk,
  publish a Release with the APK attached, copy the release link.
  The link goes in config.js.

STEP 3 - PUT THE SITE ONLINE (free)
  Option A, Netlify Drop: go to app.netlify.com/drop and drag this
  whole folder in. You get a live link in seconds.
  Option B, GitHub Pages: push the folder to a repo, enable Pages.
  (Ask Fo to do this with your GitHub account if you want.)

STEP 4 - TEST
  Open the live site on your phone: check the M-Pesa details show your
  number, fill the form with a test entry, confirm the download link
  works, and confirm admin.html saves and generates codes.

STEP 5 - KEEP ADMIN PRIVATE
  admin.html is your money book. Do not link it from index.html.
  It saves in the browser it is opened on. Export CSV now and then.

ONE REMINDER
  The app now checks activation codes: on first open it asks for a
  PTM-XXXXXX code and a 4-digit PIN, and the code only works on one
  phone. Issue a code only after M-Pesa lands, and keep admin.html
  (your buyers log) updated so you know who is paid up. If a buyer
  changes phones, generate a fresh code for them.
