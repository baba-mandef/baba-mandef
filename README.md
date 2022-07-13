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

> 🏆 312 Contributions in the Year 2022
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
🌞 Morning    227 commits    █████████░░░░░░░░░░░░░░░░   36.26% 
🌆 Daytime    174 commits    ███████░░░░░░░░░░░░░░░░░░   27.8% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   25.88% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.06%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.65% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.9% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.54% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.13% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.21% 
Saturday     99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.81% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.74%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      1 hr 3 mins         ███████████████████████░░   94.19% 
Twig                     2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.79% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.44% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  1 hr 7 mins         █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              1 hr 4 mins         ████████████████████████░   96.21% 
crispy-eureka            2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.79%

💻 Operating System: 
Linux                    1 hr 7 mins         █████████████████████████   100.0%

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


 Last Updated on 13/07/2022 18:50:41 UTC
<!--END_SECTION:waka-->
