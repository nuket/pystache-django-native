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

Requirements
------------

[Pystache](https://github.com/defunkt/pystache)

References
----------

[django.template.Template](https://docs.djangoproject.com/en/dev/ref/templates/api/#django.template.Template)
[Django - Loading templates](https://docs.djangoproject.com/en/dev/ref/templates/api/#loading-templates)
[Django - Using an alternative template language](https://docs.djangoproject.com/en/dev/ref/templates/api/#using-an-alternative-template-language)
[Django - Loader types](https://docs.djangoproject.com/en/dev/ref/templates/api/#loader-types)


License
-------

Copyright (c) 2012 Max Vilimpoc

Permission is hereby granted, free of charge, to any person obtaining 
a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom 
the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be 
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS 
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL 
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR 
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, 
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE 
OR OTHER DEALINGS IN THE SOFTWARE.