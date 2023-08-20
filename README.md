# Python Skeleton

Welcome to the **Python Skeleton** repository!  This repository provides a set of pre-configured project skeletons to kickstart your Python development journey.

Each project skeleton is contained within its own isolated folder, complete with its own README file to guide you through the setup and usage. Feel free to explore the different project types and choose the one that best suits your needs.


## Project Types

1. [Pure Python Project](./pure-python/README.md)
2. [Django Project](./django/README.md)
3. [Django Rest Framework Project](./django-rest-framework/README.md)
4. [Flask Project](./flask/README.md)
5. [FastAPI Project](./fastapi/README.md)


## Getting Started

1. Clone this repository to your local machine:
```bash
git clone https://github.com/step4ward/python-skeleton.git
cd python-skeleton
```

2. Navigate to the specific project folder of your choice:
```bash
cd python-skeleton/pure-python # Replace with the desired project folder
```

3. Follow the instructions provided in the README of the selected project folder to set up and run the project.

Choose a specific folder that interests you and navigate into it. Each folder contains a starting point for specific types of Python projects. Its own README detailing the instructions.

## Using pre-commit

We use [pre-commit](https://pre-commit.com/) to ensure code quality and style consistency. This tool will automatically run checks on your code before each commit. You can find the config in .pre-commit-config.yaml

To set up `pre-commit`:
1. Install `pre-commit` following the instruction from pre-commit official documentation -> https://pre-commit.com/#install
2. Install the pre-commit hooks:
```bash
pre-commit install
```

After setting up `pre-commit`, your changes will be automatically checked before each commit. If any issues are found, you'll need to fix them before proceeding with the commit.


## Contributing
We welcome contributions to this repository! If you'd like to add support for additional project types, improve existing skeletons, or fix any issues, feel free to open a pull request. Please refer to our [Contribution Guidelines](./CONTRIBUTING.md) for more information.


## License
This repository is licensed under the [MIT License](./LICENSE). Feel free to use, modify, and distribute the code as you see fit.


Happy coding and learning! Remember, each step forward is a step closer to mastery. If you have any questions or need assistance, feel free to open an issue or reach out to us.

Created by the *Step4ward* Team
