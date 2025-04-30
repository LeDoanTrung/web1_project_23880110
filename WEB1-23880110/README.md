sudo npm install -g handlebars
handlebars templates/about/*.hbs -f js/about.templates.js -o
handlebars templates/blogs/*.hbs -f js/blogs.templates.js -k each -k if -k formatDate -k pagination -k unless
handlebars templates/gallery/*.hbs -f js/gallery.templates.js -o
handlebars templates/index/*.hbs -f js/index.templates.js -o
handlebars templates/search/*.hbs -f js/search.templates.js -o