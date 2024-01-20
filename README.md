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

All settings are optional, so even if you don't provide any settings, the above settings are
the default settings.
