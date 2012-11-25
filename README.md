freeport
========

Find first free (not used by any program) TCP port in given range

Usage: `freeport \[START\_PORT\] \[END\_PORT\]`

Defaults:
*   START\_PORT - 8000
*   END\_PORT   - START\_PORT + 1000


Example usage:
--------------

    $ ./manage.py runserver `freeport`
    $ tty.js --port `freeport 8100`
