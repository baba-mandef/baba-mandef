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
HTML          5 hrs 33 mins         ██████████▓░░░░░░░░░░░░░░   43.21 %
Python        3 hrs 43 mins         ███████▒░░░░░░░░░░░░░░░░░   28.95 %
Other         3 hrs 5 mins          ██████░░░░░░░░░░░░░░░░░░░   23.96 %
Git Config    20 mins               ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.66 %
Text          6 mins                ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.81 %
```

<!--END_SECTION:waka-->
