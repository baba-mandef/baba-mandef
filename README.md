###
```python
from rest_framework.views import APIView
from rest_framework.response import Response

class AboutMe(APIView):

    def get(self, request):

        shadowcompiler={"fullName": "Salaou-Deen Henri-Joël Abiodoun PARAISO",

                        "stack": { "languages": ['Python', 'Php', 'JS', 'Kotlin'],
                                    "tools": ['Django', 'DRF', 'VueJS', 'NuxtJS', 'Bulma', 'Beufy'],
                                    "databases": ['Mysql', 'Postgresql', 'Sqlite'],
                                    "architectures": ["REST", "PWA", "SPA"]
                                },

                        "roles": ["Web & Mobile dev as freelance", "Blogger", "Founder at @henrid3v"],

                        "askMe": ['Food', 'Manga', 'Science', 'Comics', 'NaturalHair', 'Photography', 'Tech', 'Programming'],

                        "contacts": { 'Telegram': '@imsadi',
                                      'Linkedin': '@henri-dev',
                                      'Discord': 'ShadowCompiler#2596',
                                      'Mail':'pariso03henri@gmail.com',


                        }

                        }

```                    

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
