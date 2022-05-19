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
> 📦 31.1 kB Used in GitHub's Storage 
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
PHP                      25 hrs 23 mins      █████████████████████░░░░   86.19% 
HTML                     2 hrs 4 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.02% 
JavaScript               1 hr 18 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.45% 
Markdown                 29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65% 
Python                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

🔥 Editors: 
VS Code                  29 hrs 25 mins      █████████████████████████   99.91% 
Unknown Editor           1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🐱‍💻 Projects: 
westec                   25 hrs 12 mins      █████████████████████░░░░   85.55% 
startesk                 2 hrs 55 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   9.95% 
phplate                  41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35% 
CAEB                     36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06% 
Terminal                 1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

💻 Operating System: 
Linux                    29 hrs 27 mins      █████████████████████████   100.0%

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


 Last Updated on 19/05/2022 18:59:43 UTC
<!--END_SECTION:waka-->
