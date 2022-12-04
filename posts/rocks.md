---
title: Rocks
description: This is a photo called rocks
date: 2022-11-21
tags:
  - photo
layout: layouts/post.njk
image: /img/w3images/rocks.jpg
---
21/11/2022
1. Added images to img> W3images
2. Replaced index.njk
3. Added Avatar thumbnail to Navigation div on base.njk
4. Updated metadata.json with personal and site details.
5. Added Font Awesome Favicons to navFav.json (but it didnt like fa-chart-area, too new, use this list https://www.fontawesomecheatsheet.com/font-awesome-cheatsheet-4x/)
6. Created navigation items by folder and index.md file - didnt actually dpo this yet as want to sort responsive image out first.  Thoughts on this are upload latest w3.css and chekc that posts not knocked out as these are the things that seem skewy.  Also have a nother look at index.css, you messed about with tmpl-post in the original file, (think you copied the li item)
Navigation
1. to create an entry in the nav bar to an anchor create a njk like resources.njk 
2. to create a nav link to a folder with an index.md , its worth trying to see if you can create an md in the main directory with a different name to index.md, that said the way the About item has been created woudl suggest otherwise.


![alt text]({{ image | url }} "Chef")

Sed eu imperdiet augue. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Ut dignissim purus eu augue euismod, eget tempor velit ullamcorper. Cras in ullamcorper lectus. Quisque eleifend nibh eget dolor tincidunt, a facilisis mauris semper. Aenean tincidunt felis sem, eu rutrum ante posuere sed. Aliquam leo sapien, pulvinar sit amet enim sit amet, feugiat interdum felis. Aenean scelerisque pellentesque ante in pellentesque. Nulla eu sagittis ligula. Maecenas ut mauris eros. Quisque eget ipsum eget odio fermentum imperdiet. Integer rhoncus eleifend velit, eget mattis nulla auctor eget.