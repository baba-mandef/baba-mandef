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
![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 229 Contributions in the Year 2022
 > 
> 📦 31.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    217 commits    █████████░░░░░░░░░░░░░░░░   36.53% 
🌆 Daytime    175 commits    ███████░░░░░░░░░░░░░░░░░░   29.46% 
🌃 Evening    149 commits    ██████░░░░░░░░░░░░░░░░░░░   25.08% 
🌙 Night      53 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.92%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.86% 
Tuesday      55 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.26% 
Wednesday    81 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.64% 
Thursday     75 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.63% 
Friday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.86% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Sunday       57 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.6%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   11 hrs 8 mins       ███████████░░░░░░░░░░░░░░   46.52% 
Python                   8 hrs 37 mins       █████████░░░░░░░░░░░░░░░░   35.98% 
JavaScript               1 hr 53 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.91% 
Markdown                 57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.02% 
SCSS                     51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.55%

🔥 Editors: 
VS Code                  23 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          14 hrs 10 mins      ██████████████░░░░░░░░░░░   59.16% 
schoolman                8 hrs 37 mins       █████████░░░░░░░░░░░░░░░░   36.03% 
learn-markdown           55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.85% 
henri-front              13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.96%

💻 Operating System: 
Linux                    23 hrs 57 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   46.67% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
HTML                     3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.33%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 06/03/2022 18:47:19 UTC
<!--END_SECTION:waka-->
