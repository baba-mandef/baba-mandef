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
🌞 Morning      237 commits       █████████░░░░░░░░░░░░░░░░   35.75 % 
🌆 Daytime      191 commits       ███████░░░░░░░░░░░░░░░░░░   28.81 % 
🌃 Evening      160 commits       ██████░░░░░░░░░░░░░░░░░░░   24.13 % 
🌙 Night         75 commits       ██░░░░░░░░░░░░░░░░░░░░░░░   11.31 % 

```
📅 **I'm Most Productive on Friday** 

```text
Monday         101 commits       ███░░░░░░░░░░░░░░░░░░░░░░   15.23 % 
Tuesday         68 commits       ██░░░░░░░░░░░░░░░░░░░░░░░   10.26 % 
Wednesday       88 commits       ███░░░░░░░░░░░░░░░░░░░░░░   13.27 % 
Thursday       104 commits       ████░░░░░░░░░░░░░░░░░░░░░   15.69 % 
Friday         131 commits       █████░░░░░░░░░░░░░░░░░░░░   19.76 % 
Saturday        99 commits       ███░░░░░░░░░░░░░░░░░░░░░░   14.93 % 
Sunday          72 commits       ██░░░░░░░░░░░░░░░░░░░░░░░   10.86 % 

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
No Activity Tracked This Week

🔥 Editors: 
No Activity Tracked This Week

🐱‍💻 Projects: 
No Activity Tracked This Week

💻 Operating System: 
No Activity Tracked This Week

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ██████████░░░░░░░░░░░░░░░   41.46 % 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.07 % 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   09.76 % 
Vue                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   07.32 % 
PHP                      3 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   07.32 % 

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 09/02/2023 01:30:47 UTC
<!--END_SECTION:waka-->
