razalas89@razalas89:~/Documents/Django-1.4.1/lol$ python manage.py syncdb
Traceback (most recent call last):
  File "manage.py", line 10, in <module>
    execute_from_command_line(sys.argv)
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/__init__.py", line 443, in execute_from_command_line
    utility.execute()
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/__init__.py", line 382, in execute
    self.fetch_command(subcommand).run_from_argv(self.argv)
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/base.py", line 196, in run_from_argv
    self.execute(*args, **options.__dict__)
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/base.py", line 232, in execute
    output = self.handle(*args, **options)
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/base.py", line 371, in handle
    return self.handle_noargs(**options)
  File "/usr/local/lib/python2.7/dist-packages/django/core/management/commands/syncdb.py", line 57, in handle_noargs
    cursor = connection.cursor()
  File "/usr/local/lib/python2.7/dist-packages/django/db/backends/dummy/base.py", line 15, in complain
    raise ImproperlyConfigured("settings.DATABASES is improperly configured. "
django.core.exceptions.ImproperlyConfigured: settings.DATABASES is improperly configured. Please supply the ENGINE value. Check settings documentation for more details.
razalas89@razalas89:~/Documents/Django-1.4.1/lol$ 
