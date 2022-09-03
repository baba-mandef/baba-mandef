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
![Code Time](http://img.shields.io/badge/Code%20Time-334%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-56%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 337 Contributions in the Year 2022
 > 
> 📦 36.0 kB Used in GitHub's Storage 
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
Vue.js                   7 hrs 10 mins       ████████████████████████░   97.1% 
SCSS                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.48% 
JavaScript               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

🔥 Editors: 
VS Code                  7 hrs 23 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              6 hrs 2 mins        ████████████████████░░░░░   81.69% 
henri-front              1 hr 21 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.31%

💻 Operating System: 
Linux                    7 hrs 23 mins       █████████████████████████   100.0%

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


 Last Updated on 03/09/2022 18:51:45 UTC
<!--END_SECTION:waka-->
