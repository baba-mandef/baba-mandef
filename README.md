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
![Profile Views](http://img.shields.io/badge/Profile%20Views-66-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--496%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 96 Contributions in the Year 2022
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
🌞 Morning    153 commits    ████████░░░░░░░░░░░░░░░░░   34.77% 
🌆 Daytime    147 commits    ████████░░░░░░░░░░░░░░░░░   33.41% 
🌃 Evening    109 commits    ██████░░░░░░░░░░░░░░░░░░░   24.77% 
🌙 Night      31 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   7.05%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       57 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.95% 
Tuesday      59 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.41% 
Wednesday    66 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.0% 
Thursday     67 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.23% 
Friday       85 commits     ████░░░░░░░░░░░░░░░░░░░░░   19.32% 
Saturday     62 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.09% 
Sunday       44 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.0%

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
Python                   14 repos            ████████████░░░░░░░░░░░░░   48.28% 
HTML                     5 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.24% 
CSS                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.34% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.9% 
C++                      1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 18/02/2022 18:50:08 UTC
<!--END_SECTION:waka-->
