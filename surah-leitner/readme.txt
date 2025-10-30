what is this?
=============
> Vibe coded with ChatGPT, since I don't know JS (yet).

A small web app to quickly decide for me what surah to revise next. It's fully static, so any changes to the data need to be made locally (e.g open surahs.js in Notepad) and then uploaded to Github.

surahs.js contains the CSV data for each surah:

```
level, date, surah
1, 10.09, Al-Mulk
```

level: The Leitner system level the surah is on. Surahs are moved up a level every time they are fully recited with 2 mistakes or less.
date: The date the surah was last revised, in MM.DD format.
surah: the name of the surah.

The start date of the repetition cycle is on line 15 of index.html, in yyyy-MM-DD format.