# WordPress exporter
Reads the contents of your FlatPress instance and creates a SQL script which can be run to import your FlatPress contents to WordPress.

## Usage
- Put this file in your blog root, say to /wpdump.php , then browse to http://yoursite/flatpress/wpdump.php
- Save the output as export.sql from your browser window.
- Import to the wordpress table of your database using phpMyAdmin or any analogue tool (if your WP installation is not new, do a backup before!)

IMPORTANT! Once you're done, delete it from the server!

Many thanks to the people who wrote the ruby script and thanks to native from SPBItalia for sharing. 
