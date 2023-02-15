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
    <title>Reviews average:</title>
  </head>
  <body>
    <p> id = "response"</p>
  </body>
<script>
  fetch('http://localhost:5000/average', "GET")
  .then(response => response.text())
  .then(data => {
    const container = document.getElementById('container');
    container.innerHTML = data;
  })
  .catch(error => {
    console.error('Error fetching data:', error);
  })
</script>

</html>
