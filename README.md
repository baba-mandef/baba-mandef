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
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 315 Contributions in the Year 2022
 > 
> 📦 40.2 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.57% 
🌆 Daytime    174 commits    ███████░░░░░░░░░░░░░░░░░░   27.66% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   25.76% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.02%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.58% 
Tuesday      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.02% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.47% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.06% 
Friday       116 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.44% 
Saturday     99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.74% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.7%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   1 hr 21 mins        ████████░░░░░░░░░░░░░░░░░   33.85% 
JavaScript               48 mins             █████░░░░░░░░░░░░░░░░░░░░   19.92% 
PHP                      44 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.63% 
HTML                     32 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.52% 
Twig                     19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.07%

🔥 Editors: 
VS Code                  4 hrs 1 min         █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              2 hrs 9 mins        █████████████░░░░░░░░░░░░   53.8% 
crispy-eureka            1 hr 23 mins        ████████░░░░░░░░░░░░░░░░░   34.75% 
CAEB                     26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.13% 
westec                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
gmail-signature          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

💻 Operating System: 
Linux                    4 hrs 1 min         █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ██████████░░░░░░░░░░░░░░░   40.0% 
CSS                      7 repos             █████░░░░░░░░░░░░░░░░░░░░   20.0% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   11.43% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.71% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.71%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 21/07/2022 18:58:41 UTC
<!--END_SECTION:waka-->
