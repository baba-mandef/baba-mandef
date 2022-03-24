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
![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--3%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 268 Contributions in the Year 2022
 > 
> 📦 31.9 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    234 commits    █████████░░░░░░░░░░░░░░░░   35.78% 
🌆 Daytime    192 commits    ███████░░░░░░░░░░░░░░░░░░   29.36% 
🌃 Evening    165 commits    ██████░░░░░░░░░░░░░░░░░░░   25.23% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.63%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       116 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.74% 
Tuesday      76 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.62% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.46% 
Thursday     92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.07% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.43% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.6% 
Sunday       66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.09%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   11 hrs 32 mins      █████████████████████░░░░   84.24% 
Python                   1 hr 50 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.43% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.54% 
JavaScript               6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  13 hrs 42 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          11 hrs 51 mins      █████████████████████░░░░   86.56% 
pocket-man               1 hr 16 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.34% 
schoolman                33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.09% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    13 hrs 42 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   15 repos            ████████████░░░░░░░░░░░░░   48.39% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.9% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.45% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 24/03/2022 18:52:39 UTC
<!--END_SECTION:waka-->
