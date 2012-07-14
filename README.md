# chrome extension skelton

## source directory
- src
  - *.html.haml
  - coffee/*.coffee
  - sass/*.sass

## build
     bundle install
     bundle exec guard start

## output directory
- html
  - *.html
  - js/*.js
  - css/*.css

## Sample of manifest.json

    {
        "name": "test extension",
        "version": "1.0",
        "description": "test extension",
        "background": {
            "script": "html/js/background.js"
        },
        "page_action": {
            "default_title": "test extension",
            "default_popup": "html/popup.html"
        }
    }

