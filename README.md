# JIRA-TicketScraper

This is a collection of scripts I made as part of a work task, with the specific data stripped out, to scrape through all Jira tickets in a particular space and extract certain metrics for reporting purposes. 

At a fundamental level, the script operates on a for loop, based on the amount of content in a text file that contains the ticket ID of each ticket we wish to extract that was provided by a separate script. This loop is rate limited to a single iteration every two seconds, and appends the extracted data to a csv.
