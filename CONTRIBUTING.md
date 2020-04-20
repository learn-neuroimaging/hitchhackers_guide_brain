# Contributing to this repo

There are many ways in which to contribute to the ongoing improvement of this list of tutorials and other resources useful for open science and neuroimaging.



## Asking questions or reporting an issue

You have two ways for asking questions or reporting an issue:

- Join the [Brainhack Mattermost Team](https://mattermost.brainhack.org/): there is a dedicated channel called [~tutorial-and-resources](https://mattermost.brainhack.org/brainhack/channels/tutorial-and-resources) where you can contact us.

- [Open an issue on GitHub](https://github.com/learn-neuroimaging/tutorials-and-resources/issues/).



## Proposing a new resource (software, website, etc.)

Simply [Open an issue on GitHub](https://github.com/learn-neuroimaging/tutorials-and-resources/issues/). You will see several templates you will need to fill when proposing a new resource.

If the resource you want to add is not in the list of templates, no worries! Simply try to detail what you would like to add in this project and we will discuss about it.

If you do not feel comfortable with GitHub, simply contact us on the [~tutorial-and-resources](https://mattermost.brainhack.org/brainhack/channels/tutorial-and-resources) channel of the [Brainhack Mattermost Team](https://mattermost.brainhack.org/).



## Making direct contributions

If this is your first time contributing to an open source project, please read this very clear [tutorial](https://github.com/firstcontributions/first-contributions). You will find how to **fork** this project, **clone** your fork, make a **branch**, add modifications and create a **pull request** using command line or [GUI tools](https://github.com/firstcontributions/first-contributions#tutorials-using-other-tools).

To sum up these steps:

- Go to https://github.com/learn-neuroimaging/tutorials-and-resources and click
  the "Fork" button to create your own copy of the project.

- Clone the project to your local computer:
```
git clone git@github.com:<username>/tutorials-and-resources.git
```
where `<username>` is your GitHub username.

- Create a branch for the feature you want to work on. Since the branch name
  will appear on the pull request, use a meaningful name:
```
git checkout -b <branch_name>
```
(e.g. `git checkout -b fix_title`)

- Commit locally as you progress (`git add` and `git commit`)

- To push your changes to your fork on GitHub, type:
```
git push origin <branch_name>
```

- Go to GitHub. The new branch will show up with a green Pull Request button. Simply click it.

- You pull request will be under review. A friendly discussion with the reviewer(s) will be done in order to improve the quality of your contribution if needed. If so, update your pull request until your changes are pushed up. The pull request will update automatically and will finally be merged by the reviewer(s).



## Coding/style conventions

Currently, this project does not have a consistent style for Markdown files nor possible lines of code. This is currently [under discussion](https://github.com/learn-neuroimaging/tutorials-and-resources/issues/55).



## Testing locally

This project uses [MkDocs](https://www.mkdocs.org/) tool with [Material theme](https://squidfunk.github.io/mkdocs-material/) and extra plugins to generate the website.

- To test locally, you will need to install the dependencies. To do that, type the following commands:
```
git clone https://github.com/learn-neuroimaging/tutorials-and-resources.git
cd tutorials-and-resources
pip install -r requirements.txt
```
(If you are working on your *fork*, simply replace `https://github.com/learn-neuroimaging/tutorials-and-resources.git` by `git clone git@github.com:<username>/tutorials-and-resources.git` where
`<username>` is your GitHub username)

- Once done, you need to run MkDocs. Simply type:
```
mkdocs serve
```

- Finally, open up [`http://127.0.0.1:8000/`](http://127.0.0.1:8000/) in your browser, and you should see the default home page being displayed.


## License
By contributing, you agree that your contributions will be licensed under its
_<LICENSE>_ License.



## Recognizing contributions

We welcome and recognize all contributions!

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!
