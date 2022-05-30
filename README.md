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

![Profile Views](http://img.shields.io/badge/Profile%20Views-20-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-24%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 309 Contributions in the Year 2022
 > 
> 📦 38.7 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    228 commits    █████████░░░░░░░░░░░░░░░░   36.42% 
🌆 Daytime    173 commits    ███████░░░░░░░░░░░░░░░░░░   27.64% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   25.88% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.06%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.81% 
Tuesday      61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.74% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.54% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.13% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.05% 
Saturday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.13% 
Sunday       60 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.58%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      13 hrs 8 mins       ████████████████████████░   97.12% 
HTML                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.47% 
SQL                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  13 hrs 32 mins      █████████████████████████   100.0% 
PyCharm                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🐱‍💻 Projects: 
westec                   10 hrs 45 mins      ████████████████████░░░░░   79.52% 
startesk                 2 hrs 20 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.34% 
Performance              25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.14% 
imole_backend            0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

💻 Operating System: 
Linux                    13 hrs 32 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ███████████░░░░░░░░░░░░░░   44.74% 
CSS                      6 repos             ████░░░░░░░░░░░░░░░░░░░░░   15.79% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.53% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   7.89% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.26%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 30/05/2022 18:55:27 UTC
<!--END_SECTION:waka-->
