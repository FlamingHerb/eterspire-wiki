# Eterspire Wiki Parser

Currently, only the **Monster Parser** (`monster_parser.py`) is availabe. I'm just one guy, so expect it to be a slow crawl.

Requires [Python 3.7 and above](https://www.python.org/).

## `monster_parser.py`

To properly create new tabulations for the wiki:
1. Add new items in `wikistuff_2.json` (<sub>the other JSON file is an old version, don't bother with that</sub>).
2. Run `monster_parser.py` with the proper arguments. (e.g. `python monster_parser.py 42 69`).
3. Get the new table at `new_table.txt`!
