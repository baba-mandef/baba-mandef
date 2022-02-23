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
![Profile Views](http://img.shields.io/badge/Profile%20Views-3-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-490%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 132 Contributions in the Year 2022
 > 
> 📦 31.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    190 commits    █████████░░░░░░░░░░░░░░░░   35.65% 
🌆 Daytime    169 commits    ████████░░░░░░░░░░░░░░░░░   31.71% 
🌃 Evening    144 commits    ██████░░░░░░░░░░░░░░░░░░░   27.02% 
🌙 Night      30 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   5.63%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       83 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.57% 
Tuesday      62 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.63% 
Wednesday    77 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.45% 
Thursday     76 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.26% 
Friday       107 commits    █████░░░░░░░░░░░░░░░░░░░░   20.08% 
Saturday     84 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.76% 
Sunday       44 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.26%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   8 hrs 15 mins       ███████████████████████░░   93.65% 
Vue.js                   18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.42% 
HTML                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62% 
Bash                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  8 hrs 25 mins       ████████████████████████░   95.55% 
PyCharm                  23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.45%

🐱‍💻 Projects: 
schoolman                8 hrs 29 mins       ████████████████████████░   96.41% 
henri-front              18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.47% 
olanike                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    8 hrs 48 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   46.67% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.33%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 23/02/2022 18:50:39 UTC
<!--END_SECTION:waka-->
