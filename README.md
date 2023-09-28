Pegasus App Template
====================

App templates for SaaS Pegasus apps.

Changes from the [default Django template](https://github.com/django/django/tree/main/django/conf/app_template):

1. Include a `urls.py` file, and a "hello world" view/url.
2. Tests are set up in a module instead of `tests.py` file.
3. App is assumed to be installed in an `apps/` subdirectory.


## Installation

To use this, create the app directory:

```
mkdir apps/my_new_app
```

Then run with the following arguments:

```
./manage.py startapp my_new_app apps/my_new_app/ --template=/path/to/this/app_template/
```
