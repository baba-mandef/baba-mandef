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
![Profile Views](http://img.shields.io/badge/Profile%20Views-8-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 246 Contributions in the Year 2022
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
🌞 Morning    219 commits    █████████░░░░░░░░░░░░░░░░   36.26% 
🌆 Daytime    176 commits    ███████░░░░░░░░░░░░░░░░░░   29.14% 
🌃 Evening    148 commits    ██████░░░░░░░░░░░░░░░░░░░   24.5% 
🌙 Night      61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.1%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       116 commits    ████░░░░░░░░░░░░░░░░░░░░░   19.21% 
Tuesday      55 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.11% 
Wednesday    81 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.41% 
Thursday     72 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.92% 
Friday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.54% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.89% 
Sunday       66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.93%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   13 hrs 50 mins      ███████████████░░░░░░░░░░   60.36% 
Python                   4 hrs 55 mins       █████░░░░░░░░░░░░░░░░░░░░   21.45% 
JavaScript               1 hr 53 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.27% 
Markdown                 55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.06% 
SCSS                     51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.75%

🔥 Editors: 
VS Code                  22 hrs 55 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman-front          17 hrs 4 mins       ██████████████████░░░░░░░   74.48% 
schoolman                4 hrs 55 mins       █████░░░░░░░░░░░░░░░░░░░░   21.49% 
learn-markdown           55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.03%

💻 Operating System: 
Linux                    22 hrs 55 mins      █████████████████████████   100.0%

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


 Last Updated on 08/03/2022 18:48:58 UTC
<!--END_SECTION:waka-->
