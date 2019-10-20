# clamp
free-ware, open source modern accounting app programmed in LAMP

to install:

1. download XAMPP
2. load phpmyadmin in localhost browser
3. import daka.sql

TODO:

1.  insert all account names and asset and liability types
2.  write PHP supporting scripts for input journalizing and cyclical reporting
3.  write financial reporting and accounting formulas to apply cyclically as metrics

SOURCES:

1.  instructions to download XAMPP: https://www.apachefriends.org/download.html
2.  mysql schema tables: https://stackoverflow.com/a/15583160
3.  chart of accounts: https://www.accountingcoach.com/chart-of-accounts/explanation
4.  financial analysis metrics bibliographic citation: 

“Corporate Finance for Dummies.” Corporate Finance for Dummies, by Michael Taillard, John Wiley, 2013, pp. 73–95.

TODO:

I am considering Python for archiving and finance metrics encapsulated as serialized objects in an OO database according to this research paper:

https://docs.google.com/document/d/17Y_Y1Qc3tLRHEld70q0Mp5qM42EW6orLnnYZyIon3AQ

Persistent objects may be a good choice for archiving legacy data by month, quarter, and annual cycles running Python scripts temporally from cron and for this would need to expand the database schema with a long blob serialized object table
