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
![Code Time](http://img.shields.io/badge/Code%20Time-429%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-11-blue)

**🐱 My GitHub Data** 

> 🏆 24 Contributions in the Year 2023
 > 
> 📦 59.3 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 27 Public Repositories 
 > 
> 🔑 16 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    240 commits    █████████░░░░░░░░░░░░░░░░   35.77% 
🌆 Daytime    196 commits    ███████░░░░░░░░░░░░░░░░░░   29.21% 
🌃 Evening    160 commits    ██████░░░░░░░░░░░░░░░░░░░   23.85% 
🌙 Night      75 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.18%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       103 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.35% 
Tuesday      72 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.73% 
Wednesday    92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.71% 
Thursday     103 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.35% 
Friday       130 commits    ████░░░░░░░░░░░░░░░░░░░░░   19.37% 
Saturday     98 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.61% 
Sunday       73 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.88%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               7 hrs 3 mins        ████████████████████░░░░░   81.17% 
HTML                     40 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.81% 
Python                   19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.73% 
CSS                      16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.11% 
Other                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.46%

🔥 Editors: 
VS Code                  8 hrs 41 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              8 hrs               ███████████████████████░░   92.08% 
schoolman                21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.04% 
techmax                  20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.88%

💻 Operating System: 
Linux                    8 hrs 41 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ██████████░░░░░░░░░░░░░░░   41.46% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.07% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.76% 
Vue                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.32% 
PHP                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.32%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/ptahemdjehuty/ptahemdjehuty/main/charts/bar_graph.png) 


 Last Updated on 01/03/2023 15:57:31 UTC
<!--END_SECTION:waka-->
