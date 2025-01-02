# Initial Development of Brain Code Camp (BCC)
This is the repository that was used to develop the first version of the Brain Code Camp platform back in 2023. For the most updated version of the Brain Code Camp platform, please visit [the official Brain Code Camp organization](https://github.com/braincodecamp).

Versions
- [BCC2023](https://course2023-braincodecamp.web.app)
- [BCC2024](https://course2024-braincodecamp.web.app)

## Build Instructions

    # using python >=3.10
    pip install jupyter-book
    jupyter-book clean .
    jupyter-book build .


## Build Instructions Poetry

    # install poetry https://python-poetry.org/docs/
    poetry install
    poetry run jupyter-book clean .
    poetry run jupyter-book build .
