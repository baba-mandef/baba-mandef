###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        shadowcompiler= {
        "fullName": "Salaou-Deen Henri-Joël Abiodoun PARAISO",
        "stack": { "languages": ['Python', 'Php', 'JS', 'Kotlin'],
                   "tools": ['Django', 'DRF', 'VueJS', 'NuxtJS', 'Bulma', 'Beufy'],
                   "databases": ['Mysql', 'Postgresql', 'Sqlite'],
                   "architectures": ["MVC", "MVT", "REST", "PWA", "SPA"]},        
        "roles": ["Web & Mobile dev as freelance", "Blogger", "Founder at @henrid3v", "Mentor"],
        "askMe": ['Food', 'Manga', 'Science', 'Comics', 'NaturalHair', 'Photography', 'Tech', 'Programming'],
        "contacts": { 'Telegram': 'imsadi',
                       'Linkedin': 'henri-dev',
                       'Discord': 'ShadowCompiler#2596',
                       'Mail':'pariso03henri@gmail.com',}}
        return Response(shadowcompiler, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-24%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 306 Contributions in the Year 2022
 > 
> 📦 30.9 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 12 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.51% 
🌆 Daytime    176 commits    ███████░░░░░░░░░░░░░░░░░░   27.94% 
🌃 Evening    161 commits    ██████░░░░░░░░░░░░░░░░░░░   25.56% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.0%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.71% 
Tuesday      60 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.52% 
Wednesday    90 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
Thursday     103 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.35% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.94% 
Saturday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.03% 
Sunday       64 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.16%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 56 mins       ███████████████░░░░░░░░░░   62.88% 
HTML                     1 hr 12 mins        ██████░░░░░░░░░░░░░░░░░░░   25.82% 
JavaScript               30 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.73% 
Other                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  4 hrs 39 mins       ████████████████████████░   99.43% 
Unknown Editor           1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🐱‍💻 Projects: 
westec                   4 hrs 39 mins       ████████████████████████░   99.43% 
Terminal                 1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57%

💻 Operating System: 
Linux                    4 hrs 41 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ███████████░░░░░░░░░░░░░░   47.22% 
CSS                      6 repos             ████░░░░░░░░░░░░░░░░░░░░░   16.67% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.33% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.33% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 15/05/2022 18:54:14 UTC
<!--END_SECTION:waka-->
