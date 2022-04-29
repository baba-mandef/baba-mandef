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
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-23%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 301 Contributions in the Year 2022
 > 
> 📦 57.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 23 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    239 commits    █████████░░░░░░░░░░░░░░░░   35.94% 
🌆 Daytime    196 commits    ███████░░░░░░░░░░░░░░░░░░   29.47% 
🌃 Evening    163 commits    ██████░░░░░░░░░░░░░░░░░░░   24.51% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.08%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.14% 
Tuesday      70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.53% 
Wednesday    93 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.98% 
Thursday     101 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.19% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.14% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.64% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.38%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   15 mins             ███████████████░░░░░░░░░░   61.31% 
Python                   5 mins              █████░░░░░░░░░░░░░░░░░░░░   21.63% 
JavaScript               4 mins              ████░░░░░░░░░░░░░░░░░░░░░   17.06%

🔥 Editors: 
VS Code                  25 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          20 mins             ███████████████████░░░░░░   78.37% 
schoolman                5 mins              █████░░░░░░░░░░░░░░░░░░░░   21.63%

💻 Operating System: 
Linux                    25 mins             █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ████████████░░░░░░░░░░░░░   50.0% 
CSS                      5 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.71% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.82% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.88% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 29/04/2022 18:53:38 UTC
<!--END_SECTION:waka-->
