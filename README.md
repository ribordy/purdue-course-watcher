Purdue Class Watcher
====
This is a simple ruby script which will hit myPurdue and check if there are any open seats for a given class. Currently, it takes advantage of Pushover's API to send notifications to mobile devices, but support for email is in the works.

Usage:
1. Create an "application" on Pushover and record the API token.
2. Modify watch.rb to include your application API token and user token.
3. Run the script as follows:

    ruby watch.rb CRN TERM

Note: For fall 2014, the "term" is 201410. So, if I were to query for open seats in ECON451: Game Theory for next semester, I would run the following:

    ruby watch.rb 53454 201410
