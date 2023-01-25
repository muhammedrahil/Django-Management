# Django-Management


 ### Create folder -> myapp/management/commands/ ###


### check_manage.py
```
from django.core.management.base import BaseCommand
class Command(BaseCommand):
    help = 'Update avatars based on the Member first name and last name'

    def handle(self, *args, **options):
       ...... code ....

```


``` python manage.py check_manage ```
