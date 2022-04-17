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
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 296 Contributions in the Year 2022
 > 
> 📦 32.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 23 Public Repositories 
 > 
> 🔑 10 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    238 commits    █████████░░░░░░░░░░░░░░░░   35.52% 
🌆 Daytime    195 commits    ███████░░░░░░░░░░░░░░░░░░   29.1% 
🌃 Evening    170 commits    ██████░░░░░░░░░░░░░░░░░░░   25.37% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.0%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.01% 
Tuesday      72 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.75% 
Wednesday    93 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.88% 
Thursday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.67% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.01% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.52% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.15%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      18 hrs 28 mins      ███████████████████░░░░░░   78.88% 
HTML                     3 hrs 55 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.76% 
SCSS                     40 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.87% 
CSS                      12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

🔥 Editors: 
VS Code                  23 hrs 25 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
Unknown Project          19 hrs 15 mins      ████████████████████░░░░░   82.17% 
lift-store               4 hrs 10 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.83%

💻 Operating System: 
Linux                    23 hrs 25 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            █████████████░░░░░░░░░░░░   51.52% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.12% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.06% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.03%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 17/04/2022 18:52:08 UTC
<!--END_SECTION:waka-->
