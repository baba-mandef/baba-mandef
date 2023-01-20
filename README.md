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
![Code Time](http://img.shields.io/badge/Code%20Time-426%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-77%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 3 Contributions in the Year 2023
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
🌞 Morning    238 commits    █████████░░░░░░░░░░░░░░░░   36.06% 
🌆 Daytime    191 commits    ███████░░░░░░░░░░░░░░░░░░   28.94% 
🌃 Evening    158 commits    ██████░░░░░░░░░░░░░░░░░░░   23.94% 
🌙 Night      73 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.06%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       101 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.3% 
Tuesday      68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.3% 
Wednesday    88 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
Thursday     102 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.45% 
Friday       128 commits    ████░░░░░░░░░░░░░░░░░░░░░   19.39% 
Saturday     99 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.0% 
Sunday       74 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.21%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   13 mins             ██████████████░░░░░░░░░░░   56.8% 
JavaScript               7 mins              ███████░░░░░░░░░░░░░░░░░░   30.12% 
Python                   3 mins              ███░░░░░░░░░░░░░░░░░░░░░░   13.08%

🔥 Editors: 
VS Code                  24 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              11 mins             ███████████░░░░░░░░░░░░░░   46.03% 
schoolman-front          9 mins              ██████████░░░░░░░░░░░░░░░   40.9% 
schoolman                3 mins              ███░░░░░░░░░░░░░░░░░░░░░░   13.08%

💻 Operating System: 
Linux                    24 mins             █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ██████████░░░░░░░░░░░░░░░   40.0% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.5% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
Vue                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   7.5% 
PHP                      3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   7.5%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 20/01/2023 01:30:52 UTC
<!--END_SECTION:waka-->
