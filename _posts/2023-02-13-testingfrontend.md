---
title: Database CRUD Operations
layout: default
description: An advanced example of do database operation asynchronously between JavaScript and Backend Database.
permalink: /data/database
image: /images/database.png
categories: [C4.7, C7.0, C8.1, C8.6]
tags: [javascript, fetch, get, post, put]
---
<!DOCTYPE html>
<html> 

  
  <head>
    <title>Review's Average: </title>
  </head>
  <body>
    <p id="response"></p>
    <script>
        const url = "http://localhost:5000/";
        const options = {
          method: 'GET', // *GET, POST, PUT, DELETE, etc.
          mode: 'cors', // no-cors, *cors, same-origin
          cache: 'default', // *default, no-cache, reload, force-cache, only-if-cached
          credentials: 'omit', // include, *same-origin, omit
          headers: {
            'Content-Type': 'application/json',
            'Access-Control-Allow-Origin':'http://localhost:5000/',
            'Access-Control-Allow-Methods':'GET'
      },
    };
      // 'Content-Type': 'application/x-www-form-urlencoded',
    function displayav() {
      fetch(url, options)
        .then(response => response.text())
        .then(data => {
          console.log('The average rate is: ' + data)
          })
        .catch(error => {
          console.error('Error fetching')
        });
      };
    </script>
  </body>
</html>
