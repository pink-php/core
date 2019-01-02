# PinkPHP Core

# composer.json :
    "extra": {
        "project-files": [
            "app/_config/*",
            ".env.example"
        ],
        "public-files": [
            "assets/*",
            "favicon.ico"
        ],
        "project-files-installed": [
            "app/.htaccess",
            "app/_config.php",
            "app/_config/mysite.yml",
            "app/src/Page.php",
            "app/src/PageController.php"
        ],
        "public-files-installed": [
            ".htaccess",
            "index.php",
            "install-frameworkmissing.html",
            "install.php",
            "web.config"
        ],
        "installer-types": [
            "library",
            "component"
        ],
        "expose": [
            "vendor/twbs/bootstrap/dist/",
            "vendor/components/jquery/",
            "vendor/components/jqueryui/",
            "vendor/components/font-awesome/",
            "vendor/dimsemenov/magnific-popup/dist/",
            "vendor/soerenkroell/composer-slick/slick/"
        ]
    }
