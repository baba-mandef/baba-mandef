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
![Code Time](http://img.shields.io/badge/Code%20Time-351%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-56%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 342 Contributions in the Year 2022
 > 
> 📦 54.1 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 14 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    232 commits    █████████░░░░░░░░░░░░░░░░   36.65% 
🌆 Daytime    173 commits    ██████░░░░░░░░░░░░░░░░░░░   27.33% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   25.12% 
🌙 Night      69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.9%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       102 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.11% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.43% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.9% 
Thursday     97 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.32% 
Friday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.85% 
Saturday     98 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.48% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.9%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   2 hrs 20 mins       ███████████████████░░░░░░   77.15% 
Python                   32 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.75% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.11% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93%

🔥 Editors: 
VS Code                  3 hrs 1 min         █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              2 hrs 27 mins       ████████████████████░░░░░   81.26% 
schoolman                20 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.2% 
olanike                  13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.34% 
taskman                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

💻 Operating System: 
Linux                    3 hrs 1 min         █████████████████████████   100.0%

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


 Last Updated on 22/09/2022 18:57:27 UTC
<!--END_SECTION:waka-->
