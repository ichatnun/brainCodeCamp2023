# Initial Development of Brain Code Camp 2023
This is the repository that was used to develop the first version of the Brain Code Camp platform back in 2023. For the most updated version of the Brain Code Camp platform, please visit [the official Brain Code Camp organization](https://github.com/braincodecamp).

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
