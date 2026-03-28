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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C053%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 100 Contributions in the year 2026
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
🌞 Morning    262 commits    ██████░░░░░░░░░░░░░░░░░░░   25.71% 
🌆 Daytime    270 commits    ██████░░░░░░░░░░░░░░░░░░░   26.5% 
🌃 Evening    372 commits    █████████░░░░░░░░░░░░░░░░   36.51% 
🌙 Night      115 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.29%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       207 commits    █████░░░░░░░░░░░░░░░░░░░░   20.31% 
Tuesday      227 commits    █████░░░░░░░░░░░░░░░░░░░░   22.28% 
Wednesday    167 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.39% 
Thursday     86 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.44% 
Friday       113 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.09% 
Saturday     94 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.22% 
Sunday       125 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.27%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Python                   9 hrs 52 mins       ███████████████░░░░░░░░░░   61.08% 
Other                    2 hrs 49 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.48% 
Image (svg)              2 hrs 34 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.93% 
TOML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09% 
Markdown                 17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.84%

📝 Editors: 
VS Code                  10 hrs 45 mins      ████████████████░░░░░░░░░   66.59% 
Figma                    2 hrs 34 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.93% 
Terminal                 2 hrs 6 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.03% 
Notion                   27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.82% 
GIMP                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.63%

💻 Operating systems: 
Mac                      16 hrs 9 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 28/03/2026 19:12:05 UTC*
<!--END_SECTION:waka-->
