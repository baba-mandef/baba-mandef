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
![Profile Views](http://img.shields.io/badge/Profile%20Views-7-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 254 Contributions in the Year 2022
 > 
> 📦 31.8 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    232 commits    █████████░░░░░░░░░░░░░░░░   36.19% 
🌆 Daytime    192 commits    ███████░░░░░░░░░░░░░░░░░░   29.95% 
🌃 Evening    154 commits    ██████░░░░░░░░░░░░░░░░░░░   24.02% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.83%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       116 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.1% 
Tuesday      65 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.14% 
Wednesday    86 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.42% 
Thursday     92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.35% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.78% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.91% 
Sunday       66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.3%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   16 hrs              █████████████████░░░░░░░░   68.14% 
Python                   2 hrs 46 mins       ███░░░░░░░░░░░░░░░░░░░░░░   11.8% 
JavaScript               2 hrs 45 mins       ███░░░░░░░░░░░░░░░░░░░░░░   11.73% 
JSON                     1 hr 16 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.42% 
Other                    13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95%

🔥 Editors: 
VS Code                  23 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          19 hrs 42 mins      █████████████████████░░░░   83.89% 
schoolman                1 hr 37 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.91% 
pocket-man               1 hr 18 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.58% 
olanike                  50 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.59% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    23 hrs 29 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   45.16% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.9% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 17/03/2022 18:51:42 UTC
<!--END_SECTION:waka-->
