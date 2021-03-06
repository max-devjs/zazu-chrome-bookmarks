## Chrome Bookmarks

Chrome bookmark searcher for Zazu.

## Usage

This plugin requires a `,b` prefix, then any search term. For instance to search
your bookmarks for `github` use the following:

~~~
,b github
~~~

![screenshot](./assets/screenshot.png)

## Installing

Add the package to your plugins array in `./zazurc.js`.

~~~ javascript
{
  "plugins": [
    "tinytacoteam/zazu-chrome-bookmarks"
  ]
}
~~~

By default we look for your default profile located at:

~~~
~/Library/Application Support/Google/Chrome/Default/Bookmarks
~~~

To overwrite it, set the `file` variable:

~~~ javascript
{
  "name": "tinytacoteam/zazu-chrome-bookmarks",
  "variables": {
    "file": "~/Library/Application Support/Google/Chrome/Profile 1/Bookmarks"
  }
}
~~~
