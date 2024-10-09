# LLP - IS4242 - Group Project

## Project Python Environment
To ensure that we all have the same python development environment, we can use `pipenv`. 

Here is a description of the approach: https://chatgpt.com/share/67060b79-9cb4-8010-a7c2-c638b32744ea

To get pipenv installed
```pip install pipenv```

For any **new team member** (or even existing members who need to recreate the environment), all they need is the project’s Pipfile and Pipfile.lock. They can set up their environment by running:
```pipenv install --dev```

This command installs all dependencies (including development ones) as defined in the lock file, ensuring that everyone uses the same versions of every package.


