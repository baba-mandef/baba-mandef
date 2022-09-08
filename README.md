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
![Code Time](http://img.shields.io/badge/Code%20Time-342%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-56%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 337 Contributions in the Year 2022
 > 
> 📦 36.1 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    230 commits    █████████░░░░░░░░░░░░░░░░   36.28% 
🌆 Daytime    176 commits    ███████░░░░░░░░░░░░░░░░░░   27.76% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   25.08% 
🌙 Night      69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.88%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.62% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.41% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.88% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.93% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.82% 
Saturday     98 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.46% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.88%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   8 hrs 19 mins       ███████████████████████░░   93.39% 
JavaScript               20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.78% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.14% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64% 
XML                      2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

🔥 Editors: 
VS Code                  8 hrs 54 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
henri-front              7 hrs 27 mins       █████████████████████░░░░   83.81% 
lemocontrol              1 hr 26 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.19%

💻 Operating System: 
Linux                    8 hrs 54 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   15 repos            ██████████░░░░░░░░░░░░░░░   41.67% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   19.44% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   11.11% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.56% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.56%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 08/09/2022 18:57:36 UTC
<!--END_SECTION:waka-->
