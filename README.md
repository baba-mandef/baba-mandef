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

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--3%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 283 Contributions in the Year 2022
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
🌞 Morning    236 commits    █████████░░░░░░░░░░░░░░░░   35.87% 
🌆 Daytime    190 commits    ███████░░░░░░░░░░░░░░░░░░   28.88% 
🌃 Evening    168 commits    ██████░░░░░░░░░░░░░░░░░░░   25.53% 
🌙 Night      64 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.73%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Tuesday      69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.49% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.37% 
Thursday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.5% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.33% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.81% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.33%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   2 hrs 38 mins       ███████████░░░░░░░░░░░░░░   45.16% 
Vue.js                   2 hrs 20 mins       ██████████░░░░░░░░░░░░░░░   40.01% 
YAML                     15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.44% 
Markdown                 14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.16% 
Bash                     14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.1%

🔥 Editors: 
VS Code                  5 hrs 51 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          2 hrs 25 mins       ██████████░░░░░░░░░░░░░░░   41.39% 
backend_test             1 hr 39 mins        ███████░░░░░░░░░░░░░░░░░░   28.37% 
pocket-man               1 hr 16 mins        █████░░░░░░░░░░░░░░░░░░░░   21.82% 
schoolman                29 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.41%

💻 Operating System: 
Linux                    5 hrs 51 mins       █████████████████████████   100.0%

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


 Last Updated on 27/03/2022 18:50:41 UTC
<!--END_SECTION:waka-->
