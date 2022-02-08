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
![Code Time](http://img.shields.io/badge/Code%20Time-5%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-62-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--652%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 43 Contributions in the Year 2022
 > 
> 📦 34.9 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 24 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    130 commits    ████████░░░░░░░░░░░░░░░░░   33.16% 
🌆 Daytime    137 commits    ████████░░░░░░░░░░░░░░░░░   34.95% 
🌃 Evening    94 commits     ██████░░░░░░░░░░░░░░░░░░░   23.98% 
🌙 Night      31 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   7.91%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       47 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.99% 
Tuesday      44 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.22% 
Wednesday    68 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.35% 
Thursday     61 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.56% 
Friday       70 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.86% 
Saturday     59 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.05% 
Sunday       43 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.97%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   4 hrs 56 mins       ████████████████████████░   96.43% 
Bash                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.76% 
YAML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
PyCharm                  5 hrs 5 mins        ████████████████████████░   99.19% 
VS Code                  2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81%

🐱‍💻 Projects: 
schoolman                5 hrs 5 mins        ████████████████████████░   99.19% 
shadowcompiler           2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81%

💻 Operating System: 
Linux                    5 hrs 7 mins        █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            █████████████░░░░░░░░░░░░   51.85% 
HTML                     4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.81% 
CSS                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   11.11% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.41% 
C++                      1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.7%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 08/02/2022 10:01:56 UTC
<!--END_SECTION:waka-->
