# JSON file

A theme.json file is required for every theme in Croogo. This is required because themes can store useful information like menus and regions it uses, and this way it allows Croogo to query the database and make these information available to the theme without breaking MVC.

Content of an example theme.json file at app/View/Themed/MyTheme/webroot/theme.json below:

    {
      "name" : "Default",
      "description" : "Default theme for Croogo",
      "screenshot" : "screenshot.png",

      "author" : "Fahad Ibnay Heylaal",
      "authorEmail" : "contact@fahad19.com",
      "authorUrl" : "http://fahad19.com",

      "menus" : [
        "main",
        "footer"
        ],

      "regions" : [
        "right"
        ]
    }

* **name**: your theme's name
* **description**: your theme's description
* **screenshot**: a small preview of your theme placed under app/views/themed/my\_theme/webroot/img/screenshot.png
* **author**: your name
* **authorEmail**: your email
* **authorUrl**: your website
* **menus**: a list of menu aliases that the theme uses
* **regions**: a list of regions that the theme uses for showing blocks
* **vocabularies** (optional): a list of vocabulary aliases that the theme uses