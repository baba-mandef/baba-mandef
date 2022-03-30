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
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 290 Contributions in the Year 2022
 > 
> 📦 31.9 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 10 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    237 commits    █████████░░░░░░░░░░░░░░░░   35.64% 
🌆 Daytime    194 commits    ███████░░░░░░░░░░░░░░░░░░   29.17% 
🌃 Evening    170 commits    ██████░░░░░░░░░░░░░░░░░░░   25.56% 
🌙 Night      64 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.62%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.99% 
Tuesday      72 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.83% 
Wednesday    92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.83% 
Thursday     102 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.34% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.14% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.64% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.23%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   21 hrs 28 mins      ██████████████████████░░░   90.84% 
Text                     27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
YAML                     27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93% 
Bash                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.61% 
Docker                   17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.21%

🔥 Editors: 
VS Code                  23 hrs 38 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
backend_test             21 hrs 41 mins      ███████████████████████░░   91.75% 
pocket-man               1 hr 4 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.54% 
schoolman                29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.09% 
schoolman-front          18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28% 
Unknown Project          4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34%

💻 Operating System: 
Linux                    23 hrs 38 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            █████████████░░░░░░░░░░░░   51.52% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.12% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.06% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.03%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 30/03/2022 18:53:14 UTC
<!--END_SECTION:waka-->
