## 🎓 Pragmatic AI Labs | Join 1M+ ML Engineers

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#-pragmatic-ai-labs--join-1m-ml-engineers)

### 🔥 Hot Course Offers:

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#-hot-course-offers)

-   🤖 [Master GenAI Engineering](https://ds500.paiml.com/learn/course/0bbb5/) - Build Production AI Systems
-   🦀 [Learn Professional Rust](https://ds500.paiml.com/learn/course/g6u1k/) - Industry-Grade Development
-   📊 [AWS AI & Analytics](https://ds500.paiml.com/learn/course/31si1/) - Scale Your ML in Cloud
-   ⚡ [Production GenAI on AWS](https://ds500.paiml.com/learn/course/ehks1/) - Deploy at Enterprise Scale
-   🛠️ [Rust DevOps Mastery](https://ds500.paiml.com/learn/course/ex8eu/) - Automate Everything

### 🚀 Level Up Your Career:

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#-level-up-your-career)

-   💼 [Production ML Program](https://paiml.com/) - Complete MLOps & Cloud Mastery
-   🎯 [Start Learning Now](https://ds500.paiml.com/) - Fast-Track Your ML Career
-   🏢 Trusted by Fortune 500 Teams

Learn end-to-end ML engineering from industry veterans at [PAIML.COM](https://paiml.com/)

# pytest-tips-tricks

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#pytest-tips-tricks)

A primer on pytest

## Introduction to Testing with pytest

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#introduction-to-testing-with-pytest)

-   Why Test?
    -   Does anything work?
    -   Why PyTest?
-   Setup Cloud Development Environments with Local CI and Compare:
    -   Github Codespaces
    -   AWS Cloud9
    -   AWS Cloudshell
-   CI Systems with PyTest
    -   Github Actions: [https://docs.github.com/actions/automating-builds-and-tests/building-and-testing-nodejs-or-python?langId=py](https://docs.github.com/actions/automating-builds-and-tests/building-and-testing-nodejs-or-python?langId=py)
    -   AWS Code Build

## Invoking pytest

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#invoking-pytest)

-   [Overview of pytest invocation](https://docs.pytest.org/en/6.2.x/usage.html?highlight=pdb)
-   Simple version: `make test` via `python -m pytest -vv test_hello.py`
-   Adding Code Coverage: `pytest-cov` `python -m pytest -vv --cov=hello test_hello.py`
    -   [Coverage Invoke Snippit](https://github.com/noahgift/devops-from-zero/blob/main/Makefile#L7)
-   Adding Jupyter Notebook testing:
    -   nbval: [https://github.com/computationalmodelling/nbval](https://github.com/computationalmodelling/nbval)
    -   [nbval](https://github.com/noahgift/myrepo/blob/master/Makefile#L8-L10)
-   Debugging Code with PDB
    -   What is PDB and how does it work?
    -   Alternative IPDB\[[https://pypi.org/project/ipdb/](https://pypi.org/project/ipdb/)\]
    -   Invoke pytest with `--pdb`: [https://github.com/paiml/testing-in-python/blob/master/chapter6/Makefile#L2](https://github.com/paiml/testing-in-python/blob/master/chapter6/Makefile#L2)
-   Stop on fail:
    -   `pytest -x`
    -   `pytest --maxfail=2`
-   Specify Tests: [https://docs.pytest.org/en/6.2.x/usage.html?highlight=pdb#specifying-tests-selecting-tests](https://docs.pytest.org/en/6.2.x/usage.html?highlight=pdb#specifying-tests-selecting-tests)
    -   dir
    -   keyword
-   Build a report: [https://docs.pytest.org/en/6.2.x/usage.html?highlight=pdb#detailed-summary-report](https://docs.pytest.org/en/6.2.x/usage.html?highlight=pdb#detailed-summary-report)

## Advanced pytest

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#advanced-pytest)

-   Setup and Teardown
-   Testing Click CLI
-   Testing Flask API
-   Testing FastAPI

### References

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#references)

-   To use caching use this option: [https://github.com/actions/cache/blob/main/examples.md#python---pip](https://github.com/actions/cache/blob/main/examples.md#python---pip)

### Watch the pytest master class

[](https://github.com/noahgift/pytest-tips-tricks/blob/main/README.md#watch-the-pytest-master-class)

-   [Watch on YouTube](https://youtu.be/IN4qt-9bMiE)[](http://savefrom.net/?url=https%3A%2F%2Fyoutu.be%2FIN4qt-9bMiE&utm_source=opera-chromium&utm_medium=extensions&utm_campaign=link_modifier "Get a direct link")
-   [Watch on O'Reilly](https://learning.oreilly.com/videos/pytest-master-class/10132021VIDEOPAIML/10132021VIDEOPAIML-c1_s0/)
