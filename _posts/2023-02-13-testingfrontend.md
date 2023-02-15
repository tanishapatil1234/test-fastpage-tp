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
      const xhr = new XMLHttpRequest();
      xhr.onreadystatechange = function() {
        if (xhr.readyState === 4 && xhr.status === 200) {
          const response = xhr.responseText;
          const responseElement = document.getElementById("response");
          responseElement.innerHTML = response;
        }
      };
      xhr.open("GET", "http://localhost:5000/average");
      xhr.send();
    </script>
  </body>
</html>
