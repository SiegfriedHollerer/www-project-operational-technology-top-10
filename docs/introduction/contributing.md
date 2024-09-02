# Community and Contributing

Please don’t hesitate to contact the OWASP OT Top 10 project with your questions, comments, and ideas, either publicly by adding issues or providing commits on [our github page](https://github.com/OWASP/www-project-operational-technology-top-10).

Please join the [OWASP OT Top 10 Slack Channel](https://owasp.slack.com/archives/C07HDTYRA6R) to chat.

Until the Top 10 have stabilized, we aim to do a video conference every two weeks. The next one will be announced on slack (and pinned there).

## How to Contribute??

We're currently discussing and selecting the potential top 10 entries and are looking for new suggestions. If you have one, please add them as new markdown file in the [docs/the-top-10](/docs/the-top-10) directory and link it from within [index.md](/index.md)'s list of potential top 10.

You find the source code of the current version of the OWASP OT Top 10 in the `docs/` directory within the git repository.

When you check [our open issues on github](https://github.com/OWASP/www-project-operational-technology-top-10/issues), you can see that some issues are tagged with `help wanted` or `good first issue`. Choose these if you want to help out the project!

## How to test your changes locally before submitting

If you can run python, you can locally run the OWASP OT Top 10 website locally. We recommend this to test your changes before pushing them to github.

To do this, we will use `venv` to create a local python environment to install the needed `mkdocs` package.

```shell
# creates and activates a new python environment in a new `venv` directory
$ python3 -m venv venv
$ source venv/bin/activate

# install the mkdocs package
$ pip install mkdocs-material

# switch into your checked-out OWASP OT Top 10 directory
$ cd owasp-ot-top10

# run the local webserver
$ mkdocs server

# now you can point your browser to http://localhost:8000 and check
# how your changes will look like
```