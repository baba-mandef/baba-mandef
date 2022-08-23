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
![Code Time](http://img.shields.io/badge/Code%20Time-321%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 319 Contributions in the Year 2022
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
🌞 Morning    229 commits    █████████░░░░░░░░░░░░░░░░   36.7% 
🌆 Daytime    174 commits    ███████░░░░░░░░░░░░░░░░░░   27.88% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   25.48% 
🌙 Night      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.94%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.87% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.58% 
Wednesday    86 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.78% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.19% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.11% 
Saturday     98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.71% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.78%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   2 hrs 58 mins       █████████░░░░░░░░░░░░░░░░   37.51% 
Vue.js                   2 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   34.16% 
JavaScript               1 hr 11 mins        ███░░░░░░░░░░░░░░░░░░░░░░   15.01% 
HTML                     46 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.71% 
JSON                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.43%

🔥 Editors: 
VS Code                  7 hrs 57 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
f_train_bot              2 hrs 59 mins       █████████░░░░░░░░░░░░░░░░   37.53% 
lemocontrol              2 hrs 44 mins       ████████░░░░░░░░░░░░░░░░░   34.5% 
getpath                  2 hrs               ██████░░░░░░░░░░░░░░░░░░░   25.29% 
Unknown Project          12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.68%

💻 Operating System: 
Linux                    7 hrs 57 mins       █████████████████████████   100.0%

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


 Last Updated on 23/08/2022 18:53:38 UTC
<!--END_SECTION:waka-->
