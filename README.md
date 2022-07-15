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

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 314 Contributions in the Year 2022
 > 
> 📦 40.2 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    229 commits    █████████░░░░░░░░░░░░░░░░   36.46% 
🌆 Daytime    174 commits    ███████░░░░░░░░░░░░░░░░░░   27.71% 
🌃 Evening    162 commits    ██████░░░░░░░░░░░░░░░░░░░   25.8% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.03%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.61% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.87% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.49% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.08% 
Friday       116 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.47% 
Saturday     99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.76% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.71%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      45 mins             ████████████░░░░░░░░░░░░░   50.94% 
Twig                     19 mins             █████░░░░░░░░░░░░░░░░░░░░   21.73% 
Bash                     14 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.93% 
HTML                     5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.42% 
Vue.js                   4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.8%

🔥 Editors: 
VS Code                  1 hr 29 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
crispy-eureka            1 hr 23 mins        ███████████████████████░░   93.55% 
lemocontrol              5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.45%

💻 Operating System: 
Linux                    1 hr 29 mins        █████████████████████████   100.0%

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


 Last Updated on 15/07/2022 18:52:59 UTC
<!--END_SECTION:waka-->
