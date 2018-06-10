Place the .html, js, image, and css files in your HTML directory as normal.

The Python files should go in the cgi-bin folder in your directory and given 755 permissions. The location of the cgi-bin folder is system dependent. For Ubuntu, it is located in /usr/lib/cgi-bin.

The webcrawlJavascript.js assumes the Python files can be accessed at the address "/cgi-bin/FILENAME". If your cgi-bin files are accessed at a different address, enter the appropriate address at line 20 of webcrawlJavascript.js.