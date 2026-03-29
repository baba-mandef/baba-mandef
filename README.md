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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C054%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 102 Contributions in the year 2026
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
🌞 Morning    262 commits    ██████░░░░░░░░░░░░░░░░░░░   25.69% 
🌆 Daytime    270 commits    ██████░░░░░░░░░░░░░░░░░░░   26.47% 
🌃 Evening    373 commits    █████████░░░░░░░░░░░░░░░░   36.57% 
🌙 Night      115 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.27%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       207 commits    █████░░░░░░░░░░░░░░░░░░░░   20.29% 
Tuesday      227 commits    █████░░░░░░░░░░░░░░░░░░░░   22.25% 
Wednesday    167 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.37% 
Thursday     86 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.43% 
Friday       113 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.08% 
Saturday     95 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.31% 
Sunday       125 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.25%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Python                   9 hrs 41 mins       ████████████████░░░░░░░░░   67.12% 
Other                    1 hr 19 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.23% 
Image (svg)              1 hr 18 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.06% 
Markdown                 58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.7% 
TOML                     33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.86%

📝 Editors: 
VS Code                  11 hrs 47 mins      ████████████████████░░░░░   81.72% 
Figma                    1 hr 18 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.06% 
GIMP                     27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.16% 
Notion                   27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15% 
GitHubDesktop            15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.75%

💻 Operating systems: 
Mac                      14 hrs 26 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 29/03/2026 19:15:43 UTC*
<!--END_SECTION:waka-->
