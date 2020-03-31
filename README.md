# PHP-REST-API
How To Create A Simple REST API in PHP?


urls

http://localhost/api/product/read.php

# create
http://localhost/api/product/create.php

body

{
    "name" : "Amazing Pillow 2.0",
    "price" : "199",
    "description" : "The best pillow for amazing programmers.",
    "category_id" : 2,
    "created" : "2018-06-01 00:35:07"
}

# read

http://localhost/api/product/read_one.php?id=60

#update

http://localhost/api/product/update.php

body

{
    "id" : "66",
    "name" : "Amazing Pillow 3.0",
    "price" : "255",
    "description" : "The best pillow for amazing programmers.",
    "category_id" : 2,
    "created" : "2018-08-01 00:35:07"
}

# delete

http://localhost/api/product/delete.php

body

{
    "id" : "65"
}

# search

http://localhost/api/product/search.php?s=shirt

# Paginate Products

http://localhost/api/product/read_paging.php
