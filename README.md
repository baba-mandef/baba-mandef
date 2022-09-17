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
![Code Time](http://img.shields.io/badge/Code%20Time-349%20hrs%2025%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-56%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 337 Contributions in the Year 2022
 > 
> 📦 36.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    229 commits    █████████░░░░░░░░░░░░░░░░   36.35% 
🌆 Daytime    173 commits    ██████░░░░░░░░░░░░░░░░░░░   27.46% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   25.24% 
🌙 Night      69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.95%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.71% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.48% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.97% 
Thursday     97 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.4% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.94% 
Saturday     98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.56% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.95%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   4 hrs 47 mins       ███████████████████████░░   95.01% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.02% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
Python                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69%

🔥 Editors: 
VS Code                  4 hrs 58 mins       ████████████████████████░   98.65% 
PyCharm                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

🐱‍💻 Projects: 
henri-front              2 hrs 31 mins       ████████████░░░░░░░░░░░░░   50.01% 
lemocontrol              2 hrs 23 mins       ███████████░░░░░░░░░░░░░░   47.47% 
henri                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35% 
schoolman-front          3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18%

💻 Operating System: 
Linux                    5 hrs 2 mins        █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   15 repos            ██████████░░░░░░░░░░░░░░░   41.67% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   19.44% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   11.11% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.56% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.56%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 17/09/2022 18:59:35 UTC
<!--END_SECTION:waka-->
