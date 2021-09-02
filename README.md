Scraper Google Trends "Real Time Search" in browser with Developer Tools (Console Tab)

Open your browser and open link https://trends.google.com/trends/trendingsearches/realtime?geo=US&category=all

To open the developer console in Google Chrome, open the Chrome Menu in the upper-right-hand corner of the browser window and select More Tools > Developer Tools. 
You can also use Option + ⌘ + J (on macOS), or Shift + CTRL + J (on Windows/Linux).

With console mode executive my code:

Step 1:

db = document.querySelectorAll(".summary-text a")

Step 2:

let title_link = " "

Step 3:


for (let i = 0; i < db.length; i++) {
  title_link  += db[i].innerText + "\n" + db[i].href + "\n"
}

Step 4:

console.log(title_link)

Step 5:

copy(title_link)

Step 6:

All information in your PC (laptop) clipboard
