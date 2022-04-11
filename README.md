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

> 🏆 294 Contributions in the Year 2022
 > 
> 📦 32.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 10 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    237 commits    ████████░░░░░░░░░░░░░░░░░   35.43% 
🌆 Daytime    195 commits    ███████░░░░░░░░░░░░░░░░░░   29.15% 
🌃 Evening    170 commits    ██████░░░░░░░░░░░░░░░░░░░   25.41% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.01%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.04% 
Tuesday      72 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.76% 
Wednesday    92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.75% 
Thursday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.7% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.04% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.55% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.16%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      20 hrs 30 mins      ██████████████████░░░░░░░   74.21% 
JavaScript               5 hrs 12 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.83% 
HTML                     1 hr 52 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.78% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  27 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
Unknown Project          27 hrs 37 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    27 hrs 37 mins      █████████████████████████   100.0%

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


 Last Updated on 11/04/2022 18:56:05 UTC
<!--END_SECTION:waka-->
