###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C138%20hrs%2030%20mins-blue?style=flat)

![AI Code Time](http://img.shields.io/badge/AI%20Code%20Time-2%20hrs%2020%20mins-blue?style=flat)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue?style=flat)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-4.97%20million%20lines%20of%20code-blue?style=flat)

**🐱 My GitHub Data** 

> 📦 181.7 kB Used in GitHub's Storage 
 > 
> 🏆 463 Contributions in the Year 2026
 > 
> 💼 Opted to Hire
 > 
> 📜 31 Public Repositories 
 > 
> 🔑 6 Private Repositories 
 > 
📊 **This Week I Spent My Time On** 

🕑︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
<svg width="720" viewBox="0 0 720 140" xmlns="http://www.w3.org/2000/svg"><text x="0" y="16" font-family="monospace" font-size="13" fill="#c9d1d9">Python</text><text x="170" y="16" font-family="monospace" font-size="13" fill="#8b949e">1 hr 19 mins</text><rect x="280" y="6" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="6" width="138" height="8" rx="4" fill="#90CAF9"/><text x="648" y="16" font-family="monospace" font-size="12" fill="#8b949e">38.30%</text><text x="0" y="40" font-family="monospace" font-size="13" fill="#c9d1d9">JavaScript</text><text x="170" y="40" font-family="monospace" font-size="13" fill="#8b949e">1 hr</text><rect x="280" y="30" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="30" width="105" height="8" rx="4" fill="#90CAF9"/><text x="648" y="40" font-family="monospace" font-size="12" fill="#8b949e">29.20%</text><text x="0" y="64" font-family="monospace" font-size="13" fill="#c9d1d9">Image (svg)</text><text x="170" y="64" font-family="monospace" font-size="13" fill="#8b949e">41 mins</text><rect x="280" y="54" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="54" width="72" height="8" rx="4" fill="#90CAF9"/><text x="648" y="64" font-family="monospace" font-size="12" fill="#8b949e">19.94%</text><text x="0" y="88" font-family="monospace" font-size="13" fill="#c9d1d9">Other</text><text x="170" y="88" font-family="monospace" font-size="13" fill="#8b949e">20 mins</text><rect x="280" y="78" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="78" width="35" height="8" rx="4" fill="#90CAF9"/><text x="648" y="88" font-family="monospace" font-size="12" fill="#8b949e">9.81%</text><text x="0" y="112" font-family="monospace" font-size="13" fill="#c9d1d9">JSON</text><text x="170" y="112" font-family="monospace" font-size="13" fill="#8b949e">3 mins</text><rect x="280" y="102" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="102" width="7" height="8" rx="4" fill="#90CAF9"/><text x="648" y="112" font-family="monospace" font-size="12" fill="#8b949e">1.92%</text></svg>

🔥 Editors: 
<svg width="720" viewBox="0 0 720 116" xmlns="http://www.w3.org/2000/svg"><text x="0" y="16" font-family="monospace" font-size="13" fill="#c9d1d9">VS Code</text><text x="170" y="16" font-family="monospace" font-size="13" fill="#8b949e">2 hrs 25 mins</text><rect x="280" y="6" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="6" width="253" height="8" rx="4" fill="#90CAF9"/><text x="648" y="16" font-family="monospace" font-size="12" fill="#8b949e">70.25%</text><text x="0" y="40" font-family="monospace" font-size="13" fill="#c9d1d9">Figma</text><text x="170" y="40" font-family="monospace" font-size="13" fill="#8b949e">41 mins</text><rect x="280" y="30" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="30" width="72" height="8" rx="4" fill="#90CAF9"/><text x="648" y="40" font-family="monospace" font-size="12" fill="#8b949e">19.94%</text><text x="0" y="64" font-family="monospace" font-size="13" fill="#c9d1d9">Terminal</text><text x="170" y="64" font-family="monospace" font-size="13" fill="#8b949e">13 mins</text><rect x="280" y="54" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="54" width="23" height="8" rx="4" fill="#90CAF9"/><text x="648" y="64" font-family="monospace" font-size="12" fill="#8b949e">6.52%</text><text x="0" y="88" font-family="monospace" font-size="13" fill="#c9d1d9">Notion</text><text x="170" y="88" font-family="monospace" font-size="13" fill="#8b949e">6 mins</text><rect x="280" y="78" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="78" width="12" height="8" rx="4" fill="#90CAF9"/><text x="648" y="88" font-family="monospace" font-size="12" fill="#8b949e">3.29%</text></svg>

💻 Operating System: 
<svg width="720" viewBox="0 0 720 44" xmlns="http://www.w3.org/2000/svg"><text x="0" y="16" font-family="monospace" font-size="13" fill="#c9d1d9">Mac</text><text x="170" y="16" font-family="monospace" font-size="13" fill="#8b949e">3 hrs 26 mins</text><rect x="280" y="6" width="360" height="8" rx="4" fill="#172f45"/><rect x="280" y="6" width="360" height="8" rx="4" fill="#90CAF9"/><text x="648" y="16" font-family="monospace" font-size="12" fill="#8b949e">100.00%</text></svg>


🤖 **AI Coding This Week** 

```text
No AI Coding Activity Tracked This Week
```


 Last Updated on 14/10/2026 21:54:44 UTC
<!--END_SECTION:waka-->
