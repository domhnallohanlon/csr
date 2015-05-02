## Crowd-Sourced Resources

This is a simple, proof-of-concept, of gathering data from users via Google forms and then using jQuery to create a website directly from the form, without the need for a database.

### YQL

The demo relies on <a href="https://developer.yahoo.com/yql/console/#h=select+*+from+csv+where+url%3D'http%3A%2F%2Fdownload.finance.yahoo.com%2Fd%2Fquotes.csv%3Fs%3DYHOO%2CGOOG%2CAAPL%26f%3Dsl1d1t1c1ohgv%26e%3D.csv'+and+columns%3D'symbol%2Cprice%2Cdate%2Ctime%2Cchange%2Ccol1%2Chigh%2Clow%2Ccol2'" target="_blank">YQL</a> to parse the CSV file and return it as JSON for the webpage to work with.

I've built on <a href="http://tutorialzine.com/2010/08/dynamic-faq-jquery-yql-google-docs/" target="_blank"> this example</a> but had to modify the Sheets to CSV section a bit.
