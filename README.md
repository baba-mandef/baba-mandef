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
![Code Time](http://img.shields.io/badge/Code%20Time-351%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-56%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 351 Contributions in the Year 2022
 > 
> 📦 54.1 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 15 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    232 commits    █████████░░░░░░░░░░░░░░░░   36.19% 
🌆 Daytime    180 commits    ███████░░░░░░░░░░░░░░░░░░   28.08% 
🌃 Evening    159 commits    ██████░░░░░░░░░░░░░░░░░░░   24.8% 
🌙 Night      70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.92%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.91% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.3% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.73% 
Thursday     97 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.13% 
Friday       120 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.72% 
Saturday     99 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.44% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.76%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   1 hr 6 mins         █████████████░░░░░░░░░░░░   55.47% 
Python                   41 mins             ████████░░░░░░░░░░░░░░░░░   34.64% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.21% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42%

🔥 Editors: 
VS Code                  1 hr 59 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              1 hr 16 mins        ████████████████░░░░░░░░░   63.86% 
schoolman                20 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.07% 
olanike                  13 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.18% 
taskman                  9 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   7.89%

💻 Operating System: 
Linux                    1 hr 59 mins        █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ██████████░░░░░░░░░░░░░░░   43.24% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   18.92% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.81% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.41% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.41%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 24/09/2022 18:55:56 UTC
<!--END_SECTION:waka-->
