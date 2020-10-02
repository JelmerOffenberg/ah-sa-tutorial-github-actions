# Welcome to the AH CI/CD with Github Actions hands-on session.



# Exercise 1:
### Fork this repository
For this hands-on session you'll need some boilerplate code that we created for you. This ensures that you can focus on the CI/CD components instead of on irrelevant problems. To make your own copy of this repository you should fork it! A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

Fork this repository to your personal Github account. **Note**: We work on our personal accounts without any company data so that are in full control. For more information on how to fork a Github repository, check out:

<https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo>

---
# Exercise 2:
### Run pytest and pre-commit on your machine
This repository contains a sample Python based project. We've added a few tests in the tests directory. We'll now focus on running both PyTest and pre-commit. You will typically run your tests and pre-commit before pushing your code to the repository. We can reuse the knowledge from this step for the next exercise.
- Install pre-commit and run [pre-commit](https://pre-commit.com/) on the repository
- Use pytest to run the tests in this directory



---
# Exercise 3:
### Write your first Github Actions YAML file that runs pre-commit and pytest
You might want to check the extensive [documentation]( https://docs.github.com/en/free-pro-team@latest/actions) for help on syntax and definitions.

---
# Exercise 4:
### Update your Github Actions YAML file so that it triggers a test & build when the acceptance branch receives a new commit.


---
# Exercise 5a:
### Update your Github Actions YAML file so that it triggers a test & build when a pull request is initiated from acceptance to master.


---
# Exercise 5b (optional):
### Can you implement a change in your Github Actions YAML file so that it will trigger builds for certain tags?


---
# Exercise 6 - Deployment
