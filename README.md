# blogoExample
This is an example of the use of blogo static blog engine (https://github.com/arnaucube/blogo).

![blogo](https://raw.githubusercontent.com/arnaucube/blogoExample/master/blogo.png "blogo")

- The input files are inside the folder `blogo-input`.
- The configuration file is the `blogo-input/blogo.json`
- The output files are generated and stored on the project directory

The directory structure is:
```
/
----blogo --> the blogo binary file
----/blogo-input
--------all the html, js, css files and folders
----output generated files
```


To generate the output, just need to execute `blogo`:
```
./blogo
```


## Configuration
The config file `blogo.json` contains:
```js
{
  "title": "Blogo example", // title showed in the html page
  "relativePath": "", // by default empty, used when the blog is inside a
                      // subdirectory of the web, for example www.website.com/blog,
                      // in this case the 'relativePath' will be '/blog'
  "indexTemplate": "index.html", // html template for all the blog pages (main and post pages)
  "postThumbTemplate": "postThumbTemplate.html", // html template that will be used
                                                 // in the main html page to show the
                                                 // thumbs of the posts
  "posts": [   // Array containing the different blog posts.
               // The 'thumb' is the overview that
               // will be shown in the main html page.
               // The 'md' is the markdown file containing
               // the complete post text
    {
      "thumb": "postaboutcats_thumb.md",
      "md": "postaboutcats.md"
    },
    {
      "thumb": "the-empty-cube_thumb.md",
      "md": "the-empty-cube.md"
    },
    {
      "thumb": "firstpost_thumb.md",
      "md": "firstpost.md"
    }
  ],
  "copyRaw": [ // array with the folders and files that will be copied raw to the output
    "css",
    "img",
    "js"
  ]
}
```
