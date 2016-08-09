# PythonCode
Sample Python code projects

mailbox.py

mailbox.py opens the local file mbox.txt which contains data from a mailbox server such as e-mail, dates, times etc. The program parses through this file to extract every e-mail addresss, take the company name from the email address and provide a count of the most frequent company names. Simultaneously, this program creates an SQL database emaildb.sql and populates the database with the company names and provides the count for each company name.

To Run: Save mailbox.py and mbox.txt in the same folder. Run mailbox.py. emaildb.sqlite will be saved in the same folder. emaildb.sqlite is saved in the repository for reference.


tracks.py

Library.xml is a data file containing data from an itunes account such as track names, artists, genres, ratings etc. Tracks.py reads this data file, extracts the each song title, artist name, genre, album, song length and the number of plays and adds it to an sql database - tracksdb.sqlite. To speed up the process each genre, album and artist are given an id number for reference and repeat adding simiar data multiple times.

To Run: Save tracks.py and Library.xml in the same folder. Run tracks.py. tracksdb.sqlite will be saved in the same folder. tracksdb.sqlite is saved in the repository for reference.
