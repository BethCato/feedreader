feedreader 
===============================
Beth Cato - 9/15/18

Welcome to my RSS Feeds site!  This website pulls RSS feeds from different sites and displays them (with links) on this page.
To view different RSS Feeds, select the feed from the menu.

Starting run the application:

	To run the application, open the index.html file in your browser.

Changing a feed:
	
	To change which feed you want to view, open the menu by clicking on the 3 Bar icon at the top left of the screen.
	Click on the RSS feed you would like to display.


PAGE TESTS
This page contains Jasmine testing to ensure it continues to operate as designed.

To run the tests, load the page.
	Tests will run once the page is loaded.
	To rerun any tests, scroll to the bottom of the page and click on the test you want to run in the Jasmine section

Jasmine Test Suites
	1)	RSS Feeds
		a)	are defined – Ensure the RSS Feeds menu is defined.
		b)	each feed URL is defined and not empty – Test each feed URL to make sure it’s not blank
		c)	each feed name is defined and not empty – Test each feed name to make sure it’s not blank

	2)	The menu
		a)	is hidden by default – When the page loads, make sure the menu is hidden.
		b)	toggles on/off when clicked – Test to ensure the menu hides and shows when its supposed to.

	3)	Initial Entries
		a)	should have at least one entry in the feed list – Make sure the intial feed contains at least one entry.

	4)	New Feed Selection
		a)	should have different content when a new feed is loaded – make sure the loadFeed function actually replaces the feed contents.
