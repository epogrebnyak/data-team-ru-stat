This repo is created to organise some work of extracting and managing Russian economic statistics (macroeconomics, corporate reports, bank report forms). 

Community goal is to enable learning and sharing of knowledge in ETL/data analysis, best practices in Python programming and project management.

Participation 
==============

How to join
-----------
- introduce yourself in [#1](https://github.com/epogrebnyak/data-team-ru-stat/issues/1) - breifly tell about your background and what you expect to learn
- join [openstat-team](https://join.slack.com/openstat-team/shared_invite/MTk4MTUzODM3NTM4LTE0OTc1MTczODctMThhNTE3Yzc1NA) on Slack
- glance at <https://github.com/epogrebnyak/mini-kep> and <https://github.com/epogrebnyak/data-rosstat-kep> 
- read through [Data Science Cookiecutter](http://drivendata.github.io/cookiecutter-data-science/)

Current activity
-----------------
- Comments are open for [Introduction, part 1](https://github.com/epogrebnyak/data-team-ru-stat/issues/5)
- Some discussion of [suggested tools](https://github.com/epogrebnyak/data-team-ru-stat/issues/3) 

What happens next
-----------------
- Following parts of [Intro](https://github.com/epogrebnyak/data-team-ru-stat/blob/master/README.md#intro) to be published in Issues for discussion 

Specification
=============

Usercase for the project, based on:
- <https://github.com/epogrebnyak/data-team-ru-stat/issues/5#issuecomment-308968183>
- <https://github.com/epogrebnyak/mini-kep#Требования-к-программе>

Resources
=========

List of repos
-------------
Active developement:
- <https://github.com/epogrebnyak/mini-kep> that supercedes <https://github.com/epogrebnyak/data-rosstat-kep>

Stalled:
- any other data\*-something repo at <https://github.com/epogrebnyak/>

Library 
-------
- [Data Science Cookiecutter, DSCC](http://drivendata.github.io/cookiecutter-data-science/), *a logical, reasonably standardized, but flexible project structure for doing and sharing data science work* - a manual with some focus towards machine learning/larger data, but very useful to understand separation of parts of code and pipeline form raw immutable data to reports.

- [FRED](https://fred.stlouisfed.org/series/CPIAUCSL) - reference implementation of economic database with clean and easy API. A sort of indusry standard to dessiminate economic data.  

Rules
-----

**Terms of work**
- open to people interested in learning and sharing better practice in ETL/data analysis and Python programming
- some specific tasks are paid via Upwork

**Language**
- code comments are English-only
- issues and documentation may be in Russian (sometimes you have to express yourself), 
  but keep in mind English-only team members
- please provide a small summary (sentence or two of just a topic or a topic name) if you write something in Russian


TODO (EP)
=========

## Intro
- [case for machine-readable data in economic analysis](https://github.com/epogrebnyak/data-team-ru-stat/issues/5) 
- some previous background and lessons learned + experience at Upwork
- project scope and adjacent areas for ETL/data analysis
- getting to know people - career paths and self-presentation 

## Skillbase
- very modular checks to make sure everyone know common things needed for collaborative work 
- suggestiong for learning
- resumes, github profiles and self-presentation 

## Task ideas
- unit testing <https://github.com/epogrebnyak/question-kep-unittest>
- compare subprojects (eg source, processed data, tests, docs, invokation, why stalled)
- model crawler

## Organisation 
- who is who and expectations from project, see [#1](https://github.com/epogrebnyak/data-team-ru-stat/issues/1) 
- maybe need to bring in some more experienced people

Out of scope
============

Some great ideas that are not immediately in the scope of this task:
- [eqcell](https://github.com/epogrebnyak/make-xls-eqcell) - generate simple Excel sheets by instruction
- frontends:
  - [datachart.cc](http://datachart.cc) - sample github.io/Jekyll page, 
  - [ckan](https://ckan.org/) - larger server to dessiminate open data
- <https://civic.io/2015/04/01/i-hate-open-data-portals/> + yandex open data talk (TODO: link)
