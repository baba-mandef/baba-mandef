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

![Profile Views](http://img.shields.io/badge/Profile%20Views-19-blue)

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
🌞 Morning    229 commits    █████████░░░░░░░░░░░░░░░░   36.46% 
🌆 Daytime    174 commits    ███████░░░░░░░░░░░░░░░░░░   27.71% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   25.8% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.03%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.76% 
Tuesday      61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.71% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.49% 
Thursday     103 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.4% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.99% 
Saturday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.08% 
Sunday       60 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.55%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      40 hrs 58 mins      ███████████████████████░░   94.29% 
HTML                     58 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
JavaScript               41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.58% 
Markdown                 29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12% 
Python                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

🔥 Editors: 
VS Code                  43 hrs 27 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
westec                   34 hrs 48 mins      ████████████████████░░░░░   80.09% 
startesk                 7 hrs 21 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.92% 
phplate                  41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59% 
CAEB                     36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.4%

💻 Operating System: 
Linux                    43 hrs 27 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ███████████░░░░░░░░░░░░░░   45.95% 
CSS                      6 repos             ████░░░░░░░░░░░░░░░░░░░░░   16.22% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.11% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.11% 
PHP                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.41%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 23/05/2022 18:55:41 UTC
<!--END_SECTION:waka-->
