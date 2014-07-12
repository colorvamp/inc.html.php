inc.html.php
============



Documentation
=============

Data struct
-----------

The query results in an array of data, relevant indexes of this array are:

    + 'pageHeader': The response header
    + 'pageContent': The page content (usually html)





Query a single page
-------------------

```
/* Include library */
include_once('inc.html.php');

/* Query the url */
$data = html_query('http://google.com');

/* Show query data */
print_r($data);
```
