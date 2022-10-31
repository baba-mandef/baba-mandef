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
![Code Time](http://img.shields.io/badge/Code%20Time-376%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-66%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 350 Contributions in the Year 2022
 > 
> 📦 54.4 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 15 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.05% 
🌆 Daytime    179 commits    ███████░░░░░░░░░░░░░░░░░░   28.06% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   24.92% 
🌙 Night      70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.97%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       101 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.83% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.34% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.79% 
Thursday     97 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.2% 
Friday       118 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.5% 
Saturday     99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.52% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.82%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   2 hrs 37 mins       ██████████████████░░░░░░░   73.72% 
JavaScript               23 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.8% 
Other                    19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.32% 
JSON                     13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.16%

🔥 Editors: 
VS Code                  3 hrs 33 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
izi                      3 hrs 12 mins       ██████████████████████░░░   90.21% 
Unknown Project          20 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.79%

💻 Operating System: 
Windows                  3 hrs 33 mins       █████████████████████████   100.0%

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


 Last Updated on 31/10/2022 18:57:18 UTC
<!--END_SECTION:waka-->
