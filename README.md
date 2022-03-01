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
![Profile Views](http://img.shields.io/badge/Profile%20Views-4-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 198 Contributions in the Year 2022
 > 
> 📦 31.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    209 commits    █████████░░░░░░░░░░░░░░░░   36.73% 
🌆 Daytime    173 commits    ███████░░░░░░░░░░░░░░░░░░   30.4% 
🌃 Evening    141 commits    ██████░░░░░░░░░░░░░░░░░░░   24.78% 
🌙 Night      46 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.08%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       111 commits    █████░░░░░░░░░░░░░░░░░░░░   19.51% 
Tuesday      57 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.02% 
Wednesday    70 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.3% 
Thursday     72 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.65% 
Friday       112 commits    █████░░░░░░░░░░░░░░░░░░░░   19.68% 
Saturday     93 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.34% 
Sunday       54 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.49%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   9 hrs 4 mins        ██████████░░░░░░░░░░░░░░░   40.62% 
PHP                      7 hrs 57 mins       █████████░░░░░░░░░░░░░░░░   35.62% 
HTML                     2 hrs 50 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.7% 
CSS                      42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.14% 
Markdown                 36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.75%

🔥 Editors: 
VS Code                  22 hrs 7 mins       ████████████████████████░   99.08% 
WebStorm                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92%

🐱‍💻 Projects: 
Unknown Project          11 hrs 22 mins      ████████████░░░░░░░░░░░░░   50.96% 
schoolman                9 hrs 6 mins        ██████████░░░░░░░░░░░░░░░   40.76% 
olanike                  51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.88% 
schoolman-front          31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37% 
henri-front              17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34%

💻 Operating System: 
Linux                    22 hrs 19 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   46.67% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.33%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 01/03/2022 18:50:08 UTC
<!--END_SECTION:waka-->
