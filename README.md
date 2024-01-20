# Django Logfiles

This Django Admin plugin provides a simply way to view logfiles from the Django Admin
panels. 

Configuration can be set in settings.py:

```
LOGFILES = {
    'PATHS': ['/var/log/**.log'],
    'TAIL': 100,
    'SORT': ('-date',)
}
```
