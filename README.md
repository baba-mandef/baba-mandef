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
![Profile Views](http://img.shields.io/badge/Profile%20Views-64-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--388%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 84 Contributions in the Year 2022
 > 
> 📦 29.8 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    145 commits    ████████░░░░░░░░░░░░░░░░░   33.88% 
🌆 Daytime    146 commits    ████████░░░░░░░░░░░░░░░░░   34.11% 
🌃 Evening    106 commits    ██████░░░░░░░░░░░░░░░░░░░   24.77% 
🌙 Night      31 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   7.24%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       57 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.32% 
Tuesday      59 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.79% 
Wednesday    66 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.42% 
Thursday     64 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.95% 
Friday       76 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.76% 
Saturday     62 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.49% 
Sunday       44 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.28%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 13 mins      ████████████████████████░   99.08% 
Bash                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.9% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0% 
Vue.js                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  10 hrs 18 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman                10 hrs 18 mins      █████████████████████████   99.99% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01% 
henri-front              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

💻 Operating System: 
Linux                    10 hrs 18 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ████████████░░░░░░░░░░░░░   50.0% 
HTML                     4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
CSS                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.71% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.14% 
C++                      1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.57%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 17/02/2022 18:48:03 UTC
<!--END_SECTION:waka-->
