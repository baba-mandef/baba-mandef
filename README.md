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
![Code Time](http://img.shields.io/badge/Code%20Time-429%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-77%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 8 Contributions in the Year 2023
 > 
> 📦 54.7 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 26 Public Repositories 
 > 
> 🔑 16 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    238 commits    █████████░░░░░░░░░░░░░░░░   35.79% 
🌆 Daytime    191 commits    ███████░░░░░░░░░░░░░░░░░░   28.72% 
🌃 Evening    160 commits    ██████░░░░░░░░░░░░░░░░░░░   24.06% 
🌙 Night      76 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.43%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       101 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.19% 
Tuesday      68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.23% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.23% 
Thursday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.64% 
Friday       131 commits    █████░░░░░░░░░░░░░░░░░░░░   19.7% 
Saturday     99 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.89% 
Sunday       74 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.13%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   23 mins             ██████████████░░░░░░░░░░░   56.98% 
Python                   18 mins             ██████████░░░░░░░░░░░░░░░   43.02%

🔥 Editors: 
VS Code                  42 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              23 mins             ██████████████░░░░░░░░░░░   56.98% 
TFxF_Assistant           18 mins             ██████████░░░░░░░░░░░░░░░   43.02%

💻 Operating System: 
Linux                    42 mins             █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ██████████░░░░░░░░░░░░░░░   41.46% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.07% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.76% 
Vue                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.32% 
PHP                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.32%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 29/01/2023 01:40:11 UTC
<!--END_SECTION:waka-->
