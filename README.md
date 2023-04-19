# TESTING FLASK FRAMEWORK WITH PYTEST

> Following a CircleCI tutorial? This branch is the start point. Find the end point in the [main branch][main-branch].

The repository contains a RESTful API built with Flask for retrieving books from a list object defined in the API. You can use the following endpoints:

`[GET] /bookapi/books/:id` - Fetching a single book by its id.
`[GET] /bookapi/books` - Fetching all books

**Note**: <i> The data is hard-coded to keep the tutorial simple, nothing fancy</i> :)

## Installation

```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Running the Application

`FLASK_APP=api.py flask run`

The endpoints are now accessible at:

- <http://127.0.0.1:5000/bookapi/books>
- <http://127.0.0.1:5000/bookapi/books/1>

## Details

This repo is built following a tutorial published on CircleCI blog under the CircleCI Guest Writer Program.

- Blog post: [Testing Flask Framework with Pytest][blog]
- Author's GitHub profile: [Waweru Mwaura][author]

### About CircleCI Guest Writer Program

Join a team of freelance writers and write about your favorite technology topics for the CircleCI blog. Read more about the program [here][gwp-program].

Reviewers: [Ron Powell][ron], [Stanley Ndagi][stan], [Amos Omondi][amos], and [Oluyemi][yemi]

[main-branch]: https://github.com/CIRCLECI-GWP/testing-flask-pytest/tree/main
[blog]: https://circleci.com/blog/testing-flask-framework-with-pytest/
[author]: https://github.com/mwaz
[gwp-program]: https://circle.ci/3ahQxfu
[ron]: https://github.com/ronpowelljr
[stan]: https://github.com/NdagiStanley
[amos]: https://github.com/amos-o
[yemi]: https://github.com/yemiwebby
