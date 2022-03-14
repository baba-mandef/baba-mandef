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
![Profile Views](http://img.shields.io/badge/Profile%20Views-7-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 248 Contributions in the Year 2022
 > 
> 📦 31.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    234 commits    █████████░░░░░░░░░░░░░░░░   36.56% 
🌆 Daytime    192 commits    ███████░░░░░░░░░░░░░░░░░░   30.0% 
🌃 Evening    153 commits    ██████░░░░░░░░░░░░░░░░░░░   23.91% 
🌙 Night      61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.53%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       115 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.97% 
Tuesday      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.84% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.75% 
Thursday     92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.37% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.81% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.94% 
Sunday       66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.31%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   19 hrs 3 mins       ███████████████████░░░░░░   77.65% 
Python                   2 hrs 45 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   11.21% 
JavaScript               1 hr 52 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.61% 
JSON                     35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.41% 
Other                    8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

🔥 Editors: 
VS Code                  24 hrs 32 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          21 hrs 42 mins      ██████████████████████░░░   88.47% 
schoolman                1 hr 40 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.81% 
pocket-man               1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.72%

💻 Operating System: 
Linux                    24 hrs 32 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   45.16% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.9% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 14/03/2022 18:49:54 UTC
<!--END_SECTION:waka-->
