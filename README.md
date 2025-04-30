# Personal Project for WEB1 Course

This is a personal project for the WEB1 course, created by **Le Doan Trung** (Student ID: **23880110**).

## Overview

This project demonstrates the use of Handlebars templates to generate dynamic HTML content. Below are the commands used to compile the templates.

## Installation

To install Handlebars globally, run the following command:

```bash
sudo npm install -g handlebars
```

## Compilation Commands

Use the following commands to compile Handlebars templates into JavaScript files:

### About Templates
```bash
handlebars templates/about/*.hbs -f js/about.templates.js -o
```

### Blogs Templates
```bash
handlebars templates/blogs/*.hbs -f js/blogs.templates.js -k each -k if -k formatDate -k pagination -k unless
```

### Gallery Templates
```bash
handlebars templates/gallery/*.hbs -f js/gallery.templates.js -o
```

### Index Templates
```bash
handlebars templates/index/*.hbs -f js/index.templates.js -o
```

### Search Templates
```bash
handlebars templates/search/*.hbs -f js/search.templates.js -o
```

## Notes

- Ensure that Handlebars is installed globally before running the commands.
- The `-k` option is used to specify custom helpers like `each`, `if`, `formatDate`, `pagination`, and `unless`.

---
**Author:** Le Doan Trung  
**Student ID:** 23880110