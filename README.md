<!--
**nathan5280/nathan5280** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

## My Gen3 Technology Stack.
I hadn't realized how much Python 2 was holding us back until I started to dig into some of the newer 
packages only for Python 3.  It was right around Python 3.5/3.6 when we got *type hinting*, 
*dataclasses*, and *f-strings* that there was an inflection in innovation.  Maintaining code bases for both 
2.7 & 3.7 basically prevented us from leveraging these features.  

I call these packages **Gen3**.  Here is my latest tool stack:
|  | Current Package | Role | Replaced Package(s) | Rational / Best Features |
| :---: | :---            | :--- | :---                | :---     |
| <img src="https://github.com/nathan5280/nathan5280/blob/master/images/poetry-logo.png" width="256"/> | [Poetry](https://python-poetry.org/) | Project package management and publishing | <ul><li>pipenv</li><li>flit</li></ul> | <ul><li>Package management: Resolves and installs complex data science stacks faster.</li><li>Build and Publish Packages: Same tool, same *pyproject.toml* to manage the project packages and publish the package.</li></ul> |
| <img src="https://github.com/nathan5280/nathan5280/blob/master/images/pydantic-logo.png" width="256" /> | [Pydantic](https://pydantic-docs.helpmanual.io/) | Object <-> JSON parsing & validation | <ul><li>marshmallow</li><li>dataclasses-json</li></ul> | <ul><li>Natural use of type hints</li><li>Fast - Compiles with Cython.</li></ul> |
| <img src="https://github.com/nathan5280/nathan5280/blob/master/images/FastAPI-logo.png" width="256" /> | [FastAPI](https://fastapi.tiangolo.com/) | Restful APIs | <ul><li>flask</li><li>connexion</li></ul> | <ul><li>Code rules it all including auto generation of full OAS 3.x specification.</li><li>Built on top of Pydantic.</li><li>Fast - Compiles with Cython.</li></ul> |
| <img src="https://github.com/nathan5280/nathan5280/blob/master/images/prefect-logo.jpeg" width="256" /> | [Prefect](https://www.prefect.io/) | Workflow | <ul><li>directories of numbered scripts</li><li>airflow - trying to duck that generation of workflow</li></ul> | <ul><li>Run in the debugger locally.</li><li>Super active development.</li></ul> |

