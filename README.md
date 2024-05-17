# Fasest Python package

Instruction on a fastest way to create a Python package. If you know a faster way -- please send pull request.

# Instruction

Step-by-step [video][4] with a demo of instruction execution

1. Pick-up a name for your library -- check if it's not yet taken on [pypi.org][1]
2. Create a [GitHub][2] repo
3. Clone the repo locally
4. Add the code in `src/[PACKAGE_NAME]`
5. Add `pyproject.toml` and fill required parts
6. Add `README.md`
7. Commit & push the code & other files to the repo
8. Install Poetry in your terminal
```
pip install poetry
```
9. If you don't have a pypi.org account yet -- register it
10. Generate API token at pypi.org: [Account settings][3] -> API tokens -> Add API token
11. Add API token to Poetry config
```
poetry config pypi-token.pypi [YOUR_PYPI_API_TOKEN]
```
12. Do
```
cd [REPO_FOLDER]
poetry build
poetry publish
```
13. See your package to appear on pypi.org


  [1]: https://pypi.org/
  [2]: https://github.com/
  [3]: https://pypi.org/manage/account/
  [4]: https://youtu.be/2goLiz4vTss
