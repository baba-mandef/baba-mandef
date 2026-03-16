###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->

```txt
HTML          7 hrs 2 mins          ███████████▒░░░░░░░░░░░░░   45.94 %
Python        4 hrs 17 mins         ███████░░░░░░░░░░░░░░░░░░   27.99 %
Other         3 hrs 29 mins         █████▓░░░░░░░░░░░░░░░░░░░   22.81 %
Git Config    20 mins               ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.23 %
Text          6 mins                ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.68 %
```

<!--END_SECTION:waka-->
