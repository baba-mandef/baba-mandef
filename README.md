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

> 🏆 226 Contributions in the Year 2022
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
🌆 Daytime    178 commits    ███████░░░░░░░░░░░░░░░░░░   29.97% 
🌃 Evening    149 commits    ██████░░░░░░░░░░░░░░░░░░░   25.08% 
🌙 Night      50 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.42%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.86% 
Tuesday      58 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.76% 
Wednesday    81 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.64% 
Thursday     75 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.63% 
Friday       112 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.86% 
Saturday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Sunday       54 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 34 mins      █████████████░░░░░░░░░░░░   55.15% 
Vue.js                   5 hrs 35 mins       ███████░░░░░░░░░░░░░░░░░░   29.19% 
JavaScript               1 hr 7 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.87% 
Markdown                 57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.02% 
SCSS                     23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.02%

🔥 Editors: 
VS Code                  19 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
schoolman                10 hrs 37 mins      █████████████░░░░░░░░░░░░   55.39% 
schoolman-front          7 hrs 23 mins       █████████░░░░░░░░░░░░░░░░   38.54% 
learn-markdown           55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.81% 
henri-front              13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

💻 Operating System: 
Linux                    19 hrs 11 mins      █████████████████████████   100.0%

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


 Last Updated on 05/03/2022 18:50:00 UTC
<!--END_SECTION:waka-->
