These web pages are experimental, not fit for serious utility.  The data they use and store is all in your local cache, 
so it's pretty safe, but it's not backed up anywhere, and good luck finding it if you want to do something else with it.

Both programs are reasonably accurate, easy to use, and reliable in my experience.  The calendar is based on some very old, 
well-worn algorithms, but the interface is no threat to Google's.

If you want to run these on a phone, you need Termux, and I can't get into that here.  Any platform that can run
'python -m http.server 8080' (e.g.) can serve these up to your local browser.

Kalendar is a revision of kalends-calendar.  It corrects U.S. observance of holidays that fall on weekends, which slide either 
forward (Sunday to Monday) or backward (Saturday to Friday), and adds a report of the ISO week numbers of the month shown.
