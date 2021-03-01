# How does Docsify structure data?

Some keys points to start. Docsify does not render static html files. 

The developer builds the website in markdown language. Configuration for the site can be found in index.html. This file is where you can change the theme... etc. 

File structure is also very simple. In order to have multiple page you can enable a navbar like I did for this site. The documentation for this can be found [here](https://docsify.js.org/#/configuration). Simply put you must set  NavBar to true in your index.html file.

```
<script>
  window.$docsify = {
    loadSidebar: true
  }
</script>
```

This is the file structure for this website.

>-docs <br />
-- _side.md <br />
-- .nojekll <br />
-- index.html <br />
-- readme.md <br />
-- list.md <br />
-- data.md <br />
-- video.md <br />

Docsify offers lots of plugins such as emjois, copy to clipboard, edit on github, and google anaylistics. You can view more plugins for Docsify [here](https://docsify.js.org/#/plugins). Vue content can be added to a docsify website by adding a script tag.  


