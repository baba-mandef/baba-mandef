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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C052%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 78 Contributions in the year 2026
 > 
> 📦 178.8 kB Used in GitHub's storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 31 Public repositories 
 > 
> 🔑 6 Private repositories  
 > 
**I'm an early 🐤** 

```text
🌞 Morning    268 commits    ██████░░░░░░░░░░░░░░░░░░░   26.33% 
🌆 Daytime    270 commits    ██████░░░░░░░░░░░░░░░░░░░   26.52% 
🌃 Evening    366 commits    █████████░░░░░░░░░░░░░░░░   35.95% 
🌙 Night      114 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.2%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       203 commits    █████░░░░░░░░░░░░░░░░░░░░   19.94% 
Tuesday      225 commits    █████░░░░░░░░░░░░░░░░░░░░   22.1% 
Wednesday    177 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.39% 
Thursday     87 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.55% 
Friday       111 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   10.9% 
Saturday     90 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.84% 
Sunday       125 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.28%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Python                   10 hrs 28 mins      ████████░░░░░░░░░░░░░░░░░   32.75% 
Image (svg)              9 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   30.64% 
Other                    9 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   30.09% 
YAML                     41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14% 
TOML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.56%

📝 Editors: 
VS Code                  12 hrs 36 mins      █████████░░░░░░░░░░░░░░░░   39.4% 
Figma                    9 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   30.64% 
Terminal                 8 hrs 32 mins       ██████░░░░░░░░░░░░░░░░░░░   26.68% 
Notion                   1 hr 2 mins         ░░░░░░░░░░░░░░░░░░░░░░░░░   3.28%

💻 Operating systems: 
Mac                      31 hrs 59 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 25/03/2026 19:22:35 UTC*
<!--END_SECTION:waka-->
