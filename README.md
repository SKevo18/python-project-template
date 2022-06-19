# Python project template

A template for new Python projects.

## Features

- Automatically builds [PDoc](https://pdoc3.github.io/pdoc/) documentation & uploads package to [PyPI](https://pypi.org) on new GitHub release, thanks to GitHub actions;
- Tests with pyTest before uploading to PyPI (or you can test manually with `workflow-dispatch`);
- Ready-to-go `setup.py` file;
- Scripts to build documentation and compile as a Python package;
- A to-do list below;
- Possibly more ;)

## Your to-do list

- [ ] Edit `# FIXME` lines to match your project;
  - [ ] setup.py
    - [ ] Package name
    - [ ] License
    - [ ] Version
    - [ ] Author
    - [ ] Author email
    - [ ] Description
    - [ ] Keywords
    - [ ] Classifiers
    - [ ] Repository URL
- [ ] Setup virtualenv (`scripts/setup_virtualenv_windows.ps1` for Windows);
- [ ] Rename `python_project_template` folder and start writing your source code;
- [ ] Add your dependencies to `requirements.txt`;
- [ ] Update .gitingore with your stuff;
- [ ] Replace this `README.md` file with a fancier one;
- [ ] Upload code to your GitHub repository;
- [ ] Turn on GitHub pages and use `documentation` as your pages branch;
- [ ] Add your editior to `.gitignore`;
- [ ] Add your PyPI API key to GitHub secrets (`PYPI_API_TOKEN`);
- [ ] When your are done, make a new release at GitHub to build documentation and upload to PyPI;
  - Don't forget to bump version in `setup.py` everytime you do a new release!!!

Generated documentation example: https://cwkevo.github.io/python-project-template

That should be it. Happy coding!

If you have any questions or found a bug, please open a new issue in this repository.

## 🎁 Support me

I create free software to benefit people.
If this project helps you and you like it, consider supporting me by donating via [PayPal](https://www.paypal.com/donate/?hosted_button_id=XDUWS5K6947HY).
