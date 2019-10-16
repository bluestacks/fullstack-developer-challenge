# FullStack Developer Challenge

Create a website that lets user browse top android apps. The website should contain
two pages - landing page and a detail page. Please see Specs section below for UI details

* On the landing page user will see a list of all top android apps. These apps will need to be scraped from Google Play Store: https://play.google.com/store/apps/collection/topselling_free and stored in your website’s DB.
* You need to show these apps on landing page by fetching from DB.
* The landing page should also contain a button that will re-scrape all the data from the top apps page and update the entries in the DB.If new apps are available add them to your db, but do not delete the apps that have already been scraped but removed from
the top apps page.
* On clicking any app on the landing page of your website, user should be redirected to the detail page of your website where more information about the app will be shown.
* You can show things like app name, package, icon, developer name, videos, screenshots etc.
* The landing page and the detail page should be on different urls on the same domain. For example, www.yourwebsite.com/ and www.yourwebsite.com/appdetails?pkg=com.whatsapp
* User should also be able to directly enter a url with app package and the website should show the details for that app package. For example - I should be able enter this url in the browser - www.yourwebsite.com/appdetails?pkg=com.supercell.brawlstars , and all the information regarding this app should be displayed on the page.


Once you are done, please share with us:
1. Source code link (GitHub, BitBucket, etc)
2. URL where you have hosted the project

# Specs

# Need Help?

* How to create Repo in GitHub? [Click here](https://guides.github.com/activities/hello-world/) 
