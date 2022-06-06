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

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-24%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 320 Contributions in the Year 2022
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
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.16% 
🌆 Daytime    176 commits    ███████░░░░░░░░░░░░░░░░░░   27.67% 
🌃 Evening    167 commits    ██████░░░░░░░░░░░░░░░░░░░   26.26% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.91%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.57% 
Tuesday      61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.59% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.31% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.88% 
Friday       118 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.55% 
Saturday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.51% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.59%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   2 hrs 30 mins       █████████████░░░░░░░░░░░░   54.51% 
YAML                     41 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.99% 
Text                     14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.34% 
Markdown                 12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.53% 
CSS                      11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.23%

🔥 Editors: 
VS Code                  4 hrs 35 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
imole_backend            3 hrs 57 mins       █████████████████████░░░░   85.91% 
Performance              22 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.15% 
henri-front              16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.95%

💻 Operating System: 
Linux                    4 hrs 35 mins       █████████████████████████   100.0%

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


 Last Updated on 06/06/2022 18:51:21 UTC
<!--END_SECTION:waka-->
