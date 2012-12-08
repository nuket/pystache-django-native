pystache-django-native
======================

Seamlessly use Mustache, Pystache, Handlebars templates using Django's render() functions.

Installation
------------

1. Just copy the template.py file anywhere into your Django project tree.
2. Add the PystacheAppDirectoriesLoader and PystacheFilesystemLoader classes into
   the TEMPLATE\_LOADERS setting in your project's settings.py file.
3. Create template files using .mustache, .handlebars, or .hbs extensions
4. Render away with the standard render('file.handlebars', context) or render_to_response().
