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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C028%20hrs%2016%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 146 Contributions in the year 2026
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
🌞 Morning    374 commits    ███████░░░░░░░░░░░░░░░░░░   28.84% 
🌆 Daytime    342 commits    ██████░░░░░░░░░░░░░░░░░░░   26.37% 
🌃 Evening    422 commits    ████████░░░░░░░░░░░░░░░░░   32.54% 
🌙 Night      159 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.26%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       226 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.42% 
Tuesday      280 commits    █████░░░░░░░░░░░░░░░░░░░░   21.59% 
Wednesday    219 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.89% 
Thursday     149 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.49% 
Friday       169 commits    ███░░░░░░░░░░░░░░░░░░░░░░   13.03% 
Saturday     103 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   7.94% 
Sunday       151 commits    ███░░░░░░░░░░░░░░░░░░░░░░   11.64%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Other                    8 hrs 45 mins       █████████░░░░░░░░░░░░░░░░   35.97% 
Image (svg)              7 hrs 29 mins       ███████░░░░░░░░░░░░░░░░░░   30.77% 
Python                   4 hrs 1 min         ████░░░░░░░░░░░░░░░░░░░░░   16.53% 
HTML                     2 hrs 33 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   10.5% 
YAML                     41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.81%

📝 Editors: 
VS Code                  8 hrs 16 mins       ████████░░░░░░░░░░░░░░░░░   33.97% 
Figma                    7 hrs 29 mins       ███████░░░░░░░░░░░░░░░░░░   30.77% 
Terminal                 7 hrs 8 mins        ███████░░░░░░░░░░░░░░░░░░   29.32% 
GIMP                     43 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.99% 
Notion                   35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.46%

💻 Operating systems: 
Mac                      24 hrs 21 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 21/03/2026 19:04:44 UTC*
<!--END_SECTION:waka-->
