This repo is created to organise some work of extracting and managing Russian economic statistics (macroeconomics, corporate reports, bank report forms). 

Community goal is to enable learning and sharing of knowledge in ETL/data analysis, best practices in Python programming and project management.

Current activity (TODO)
-----------------------
- sample parsers (@EP, ...)
- end user api requirements (@EP, ...) 
- frontpage requirements (@EP, ...)
- database specification (@Nikita, ...)

Outstanding (FIXME)
---------------------------
- requirements are a [collection of posts](https://github.com/epogrebnyak/data-team-ru-stat/blob/master/usercase.md#to-be-aggregated-from), not a [single document](https://github.com/epogrebnyak/data-team-ru-stat/blob/master/usercase.md) 
- design (data pipeline) documented repetively in [issue 8](https://github.com/epogrebnyak/data-team-ru-stat/issues/8), 
  not a single document 

Previous activity (DONE)
-------------------------
- a roadmap draft [for minimal working pipeline and its extensions](https://github.com/epogrebnyak/data-team-ru-stat/issues/8)
- getting ready for [requirements and design live session](https://github.com/epogrebnyak/data-team-ru-stat/issues/6)
- comments are open for [Introduction, part 1](https://github.com/epogrebnyak/data-team-ru-stat/issues/5)
- some discussion of [suggested tools](https://github.com/epogrebnyak/data-team-ru-stat/issues/3) 

Library 
-------
- [Data Science Cookiecutter, DSCC](http://drivendata.github.io/cookiecutter-data-science/), *a logical, reasonably standardized, but flexible project structure for doing and sharing data science work* - a manual with some focus towards machine learning/larger data, but very useful to understand separation of parts of code and pipeline form raw immutable data to reports.

- [FRED](https://fred.stlouisfed.org/series/CPIAUCSL) - reference implementation of economic database with clean and easy API. A sort of indusry standard to dessiminate economic data.  

Rules
-----

### Terms of work
- open to people interested in learning and sharing better practice in ETL/data analysis and Python programming
- some specific tasks are paid via Upwork

### Language
- for code comments and issue headers are English-only
- issues text, discussion and parts of documentation may be in Russian, with English summary 

### When joining...
- introduce yourself in [#1](https://github.com/epogrebnyak/data-team-ru-stat/issues/1) - breifly tell about your background and what you expect to learn
- join [openstat-team](https://join.slack.com/openstat-team/shared_invite/MTk4MTUzODM3NTM4LTE0OTc1MTczODctMThhNTE3Yzc1NA) on Slack
- read through [Data Science Cookiecutter](http://drivendata.github.io/cookiecutter-data-science/) and take a look at [FRED](https://fred.stlouisfed.org/)

Out of scope (NOT TODO)
-----------------------

Some great ideas that are not immediately in the scope of this project:
- [eqcell](https://github.com/epogrebnyak/make-xls-eqcell) - generate simple Excel sheets by text instruction
- frontends:
  - [datachart.cc](http://datachart.cc) - sample github.io/Jekyll page, 
  - [ckan](https://ckan.org/) - larger server to dessiminate open data
- <https://civic.io/2015/04/01/i-hate-open-data-portals/> + yandex open data talk (TODO: link)
- unit testing <https://github.com/epogrebnyak/question-kep-unittest>
