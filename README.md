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
![Profile Views](http://img.shields.io/badge/Profile%20Views-9-blue)

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
Vue.js                   24 hrs 51 mins      █████████████████████░░░░   83.72% 
Python                   2 hrs 22 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.98% 
JavaScript               1 hr 38 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.55% 
SCSS                     28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.61% 
JSON                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.11%

🔥 Editors: 
VS Code                  29 hrs 41 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          27 hrs 19 mins      ███████████████████████░░   92.02% 
schoolman                2 hrs 22 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.98%

💻 Operating System: 
Linux                    29 hrs 41 mins      █████████████████████████   100.0%

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


 Last Updated on 12/03/2022 18:50:01 UTC
<!--END_SECTION:waka-->
