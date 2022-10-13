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
![Code Time](http://img.shields.io/badge/Code%20Time-366%20hrs%2055%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-66%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 350 Contributions in the Year 2022
 > 
> 📦 54.3 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 15 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   35.94% 
🌆 Daytime    181 commits    ███████░░░░░░░░░░░░░░░░░░   28.28% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   24.84% 
🌙 Night      70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.94%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       103 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.09% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.31% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.75% 
Thursday     97 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.16% 
Friday       118 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.44% 
Saturday     99 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.47% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.78%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   3 hrs 24 mins       ████████████████████░░░░░   82.02% 
HTML                     35 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.31% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.17% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  4 hrs 9 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              4 hrs 9 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    4 hrs 9 mins        █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ██████████░░░░░░░░░░░░░░░   42.11% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   18.42% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.53% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.26% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.26%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 13/10/2022 19:06:07 UTC
<!--END_SECTION:waka-->
