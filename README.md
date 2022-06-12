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

![Profile Views](http://img.shields.io/badge/Profile%20Views-3-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-24%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 321 Contributions in the Year 2022
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
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.11% 
🌆 Daytime    177 commits    ███████░░░░░░░░░░░░░░░░░░   27.79% 
🌃 Evening    167 commits    ██████░░░░░░░░░░░░░░░░░░░   26.22% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.89%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.54% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.73% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.86% 
Friday       118 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.52% 
Saturday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.48% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.58%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
YAML                     1 hr 3 mins         ████████████░░░░░░░░░░░░░   48.58% 
PHP                      33 mins             ██████░░░░░░░░░░░░░░░░░░░   25.9% 
JSON                     14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.12% 
Markdown                 11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.03% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.85%

🔥 Editors: 
VS Code                  2 hrs 10 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
blog                     1 hr                ███████████░░░░░░░░░░░░░░   46.63% 
landoFirst               42 mins             ████████░░░░░░░░░░░░░░░░░   32.57% 
henri-front              14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.94% 
startesk                 12 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.87%

💻 Operating System: 
Linux                    2 hrs 10 mins       █████████████████████████   100.0%

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


 Last Updated on 12/06/2022 18:49:22 UTC
<!--END_SECTION:waka-->
