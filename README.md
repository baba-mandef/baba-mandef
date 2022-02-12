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
![Profile Views](http://img.shields.io/badge/Profile%20Views-64-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-77%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 66 Contributions in the Year 2022
 > 
> 📦 35.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 24 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    138 commits    ████████░░░░░░░░░░░░░░░░░   33.58% 
🌆 Daytime    144 commits    ████████░░░░░░░░░░░░░░░░░   35.04% 
🌃 Evening    98 commits     ██████░░░░░░░░░░░░░░░░░░░   23.84% 
🌙 Night      31 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   7.54%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       48 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.68% 
Tuesday      52 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.65% 
Wednesday    67 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.3% 
Thursday     64 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.57% 
Friday       76 commits     ████░░░░░░░░░░░░░░░░░░░░░   18.49% 
Saturday     61 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.84% 
Sunday       43 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.46%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   7 hrs 17 mins       ████████████████████████░   97.49% 
Bash                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.89% 
YAML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
PyCharm                  5 hrs 5 mins        █████████████████░░░░░░░░   68.08% 
VS Code                  2 hrs 23 mins       ████████░░░░░░░░░░░░░░░░░   31.92%

🐱‍💻 Projects: 
schoolman                7 hrs 25 mins       ████████████████████████░   99.44% 
shadowcompiler           2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

💻 Operating System: 
Linux                    7 hrs 28 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ████████████░░░░░░░░░░░░░   50.0% 
HTML                     4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.29% 
CSS                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.71% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.14% 
C++                      1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.57%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 12/02/2022 18:45:58 UTC
<!--END_SECTION:waka-->
