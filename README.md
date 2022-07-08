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

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 322 Contributions in the Year 2022
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
🌞 Morning    229 commits    █████████░░░░░░░░░░░░░░░░   35.95% 
🌆 Daytime    178 commits    ███████░░░░░░░░░░░░░░░░░░   27.94% 
🌃 Evening    167 commits    ██████░░░░░░░░░░░░░░░░░░░   26.22% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.89%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.54% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.73% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
Thursday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.01% 
Friday       119 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.68% 
Saturday     103 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.17% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.58%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      1 hr 5 mins         █████████░░░░░░░░░░░░░░░░   39.02% 
HTML                     55 mins             ████████░░░░░░░░░░░░░░░░░   32.95% 
JSON                     41 mins             ██████░░░░░░░░░░░░░░░░░░░   24.84% 
Twig                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52% 
YAML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06%

🔥 Editors: 
VS Code                  2 hrs 48 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
responsive-html-email-sig1 hr 20 mins        ████████████░░░░░░░░░░░░░   47.94% 
lemocontrol              1 hr 19 mins        ███████████░░░░░░░░░░░░░░   47.3% 
blog                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.25% 
crispy-eureka            2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52%

💻 Operating System: 
Linux                    2 hrs 48 mins       █████████████████████████   100.0%

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


 Last Updated on 08/07/2022 18:56:54 UTC
<!--END_SECTION:waka-->
