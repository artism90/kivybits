# builder

Added UTF-8 reading for any kv lang files.

Just a oneliner:
> Line 287 -- with open(filename, 'r', encoding='utf-8') as fd:

It's not an approved approach by the kivy core dev team to force a certain encoding like that. Until there's a better way, it's a fast and easy fix though when just messing around with UTF-8 issues.
