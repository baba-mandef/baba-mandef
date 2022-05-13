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

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-23%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 303 Contributions in the Year 2022
 > 
> 📦 27.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    238 commits    █████████░░░░░░░░░░░░░░░░   36.62% 
🌆 Daytime    183 commits    ███████░░░░░░░░░░░░░░░░░░   28.15% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   24.92% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.31%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.23% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.54% 
Wednesday    90 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.85% 
Thursday     103 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.85% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.54% 
Saturday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.54% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.46%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Other                    1 min               █████████████████████████   100.0%

🔥 Editors: 
Unknown Editor           1 min               █████████████████████████   99.99% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🐱‍💻 Projects: 
Terminal                 1 min               █████████████████████████   100.0%

💻 Operating System: 
Linux                    1 min               █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ████████████░░░░░░░░░░░░░   48.57% 
CSS                      5 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.57% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.57% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.86%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 13/05/2022 18:56:07 UTC
<!--END_SECTION:waka-->
