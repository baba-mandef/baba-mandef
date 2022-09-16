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
![Code Time](http://img.shields.io/badge/Code%20Time-348%20hrs%209%20mins-blue)

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
Vue.js                   3 hrs 52 mins       ███████████████████████░░   94.18% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.88% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06% 
Python                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84% 
Markdown                 1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81%

🔥 Editors: 
VS Code                  4 hrs 3 mins        ████████████████████████░   98.35% 
PyCharm                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65%

🐱‍💻 Projects: 
henri-front              2 hrs 31 mins       ███████████████░░░░░░░░░░   61.18% 
lemocontrol              1 hr 28 mins        █████████░░░░░░░░░░░░░░░░   35.74% 
henri                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65% 
schoolman-front          3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.44%

💻 Operating System: 
Linux                    4 hrs 7 mins        █████████████████████████   100.0%

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


 Last Updated on 16/09/2022 19:00:37 UTC
<!--END_SECTION:waka-->
