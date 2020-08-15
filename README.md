### Hi there 👋

<!--
**nathan5280/nathan5280** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

- Python Developer
    - Poetry
    - Pydantic
- Machine Learning Engine
    - When it doesn't fit on your notebook anymore
    - When you want to deliver value to the business
- API & Backend Service Development
    - FastAPI
    - Journal / Logging
- Testing
    - It's not just coverage
    - Gamify the process
- DevOps
    - Docker - Glad to be rid of the stacks of CD's
    - GCP
- Business Communication & Requirements Gathering
    - Listening skills to understand what they are really asking for
- Problem solving
    - Curiosity
    - Aliasing
    - Knowing when to seek help
    
## My current gen-3 technology stack.
I hadn't realized how much Python 2 was holding us back until I started to dig into some of the newer 
packages that only focused on Python 3.  I think it was right around Python 3.5/3.6 when we got *type hinting*, 
*dataclasses*, and *f-strings* that there as an inflection in innovation.  Maintaining code bases for both 2.7 & 3.7 basically 
prevented us from leveraging these features.  

I've recently replaced a number of my core packages with some of these new gen-3 package.  Here is my new tool stack.

|  | Current Package | Role | Replaced Package(s) | Rational / Best Features |
| :---: | :---            | :--- | :---                | :---     |
| <img src="images/poetry-logo.png" width="256"/> | [Poetry](https://python-poetry.org/) | Project package management and publishing | <ul><li>PipEnv</li><li>Flit</li></ul> | <ul><li>Package management: Resolves and installs complex data science stacks faster.</li><li>Build and Publish Packages: Same tool, same *pyproject.toml* to manage the project packages and publish the package.</li></ul> |
| <img src="images/pydantic-logo.png" width="256" /> | [Pydantic](https://pydantic-docs.helpmanual.io/) | Object <-> JSON parsing & validation | <ul><li>marshmallow</li><li>dataclasses-json</li></ul> | <ul><li>Natural use of type hints</li><li>Fast - Compiles with Cython.</li></ul> |
| <img src="images/FastAPI-logo.png" width="256" /> | [FastAPI](https://fastapi.tiangolo.com/) | Restful APIs | <ul><li>Flask</li><li>Connexion</li></ul> | <ul><li>Code rules it all including auto generation of full OAS 3.x specification.</li><li>Built on top of Pydantic.</li><li>Fast - Compiles with Cython.</li></ul> |
| <img src="images/prefect-logo.jpeg" width="256" /> | [Prefect](https://www.prefect.io/) | Workflow | <ul><li>Numbered scripts</li><li>Ducking learning AirFlow</li></ul> | <ul><li>Run in the debugger locally.</li><li>Super active development.</li></ul> |

