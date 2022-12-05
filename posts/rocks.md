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

04/12/2022
1. Added roadmap files
2. Removed base.njk message

Navigation
1. to create an entry in the nav bar to an anchor create a njk like resources.njk 
2. to create a nav link to a folder with an index.md , its worth trying to see if you can create an md in the main directory with a different name to index.md, that said the way the About item has been created woudl suggest otherwise.

05/12/2022
1. Update CSS to December 2020 version and created copy of previous css
2. Above didnt resolve the issue directly but left file as current version as it didnt destroy site.
User w3-image as the class against one image and the responsive kicked in showing that w3.css is controling this.




![alt text]({{ image | url }} "Chef")

The message was removed from the bask.njk file
Edit the _data/metadata.json with your blog’s information.
(Optional) Edit .eleventy.js with your configuration preferences.
Delete this message from _includes/layouts/base.njk.
<div class="warning">
        <ol>
          <li>Edit the <code>_data/metadata.json</code> with your blog’s information.</li>
          <li>(Optional) Edit <code>.eleventy.js</code> with your <a href="https://www.11ty.dev/docs/config/">configuration preferences</a>.</li>
          <li>Delete this message from <code>_includes/layouts/base.njk</code>.</li>
        </ol>
        <p><em>This is an <a href="https://www.11ty.io/">Eleventy project</a> created from the <a href="https://github.com/11ty/eleventy-base-blog"><code>eleventy-base-blog</code> repo</a>.</em></p>
      </div>