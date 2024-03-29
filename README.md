 Maddy's Milestones
=================

Nothing interesting for the code community here, just super moments in my girls life.

A fork of [Life](https://github.com/cheeaun/life/) with added style and flair 💃💃💃💃💃💃💃💃💃




----
----




####How to use Life

######Datetime "syntax"

- `2000` - event that happen in that year
- `01/2000` - event that happen in that month/year
- `01/01/2000` - event that happen exactly in that day/month/year
- `2001-2005`, `10/2001-02/03/2005` - event that happen within the two dates
- `~2005` - event that happen around the time in that year
- `2005-~` - event that happen from that year and beyond (now).


######How to configure your *Life*

1. Make a copy of `config.example.json`, rename it to `config.json`.
2. Only commit it in `gh-pages` branch.

The configuration:

- `customStylesheetURL` - (*string*, default to `null`) Path to a custom stylesheet file, for those who doesn't like the default *theme*.
- `yearLength` - (*number*, default to `120`) The width of the year grids, in pixels.
- `hideAge` - (*boolean*, default to `false`) Option to hide age from year axis.


---


How to setup your own *Life*
----------------------------

1. Fork this project.
2. `git checkout -b gh-pages` (or any branch name you like)
3. Make a copy of `life.example.md`, rename it to `life.md`.
4. Add your life events into `life.md`.
5. Preview it on a local server. Use [`python -m SimpleHTTPServer`](http://docs.python.org/2/library/simplehttpserver.html) or [`http-server`](https://github.com/nodeapps/http-server).
6. Commit `life.md` (not in `master` branch).
7. `git push origin gh-pages -f` and publish to [GitHub Pages](http://pages.github.com/).
8. Update the website link in your GitHub repo description.
9. Tell the world about your Life.
10. Add your Life to the [Lives](https://github.com/cheeaun/life/wiki/Lives) page.


Use [Nitrous.IO](https://www.nitrous.io/?utm_source=github.com&utm_campaign=Life&utm_medium=hackonnitrous) to create your own *Life* in seconds:

[![Hack cheeaun/life on Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e71372f6045e1949af9d96095b.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=cheeaun%2Flife&file_to_open=README)



