This is just a repository for machinery related to translations.

Working on translations is done on Weblate:
https://hosted.weblate.org/projects/ddnet/ddnet/.

The actual translations as used in the DDNet client reside in
[data/languages](https://github.com/ddnet/ddnet/tree/master/data/languages) in
the [DDNet repository](https://github.com/ddnet/ddnet).

Only maintainers (not translators) need to convert between them.

Use `python scripts/languages/from_csv.py path/to/ddnet-translations/ddnet` to
convert from this repository's data to DDNet's translation files and `python
scripts/languages/to_csv.py path/to/ddnet-translations/ddnet` for the other
direction.
