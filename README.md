# anime-quotes

A lightweight and easy-to-use command-line tool to display random anime quotes.

## About

**anime-quotes** is a Python package that allows users to retrieve random quotes from anime characters via the command line.  
It supports filtering by character name and fetches quote data from a public GitHub repository. The quotes are cached locally for offline access after the first run.

## Installation

Install from PyPI:

```bash
pip install anime-quotes
```

## Usage

Displays a random quote:
```bash
anime-quote
```

Displays a quote from the character "Goku":
```bash
anime-quote goku
```

> Note: An internet connection is required on the first run to download quote data.

## Data Source

Quotes are fetched in real-time from the following GitHub repository:

[miya3333](https://github.com/miya3333/anime-quotes-data)

Contributions to the quote database are welcome.


## Terms of Use

1. This package retrieves quote data from an open GitHub repository.
2. Offline use is supported after initial data retrieval.
3. Do not redistribute the content without appropriate credit.
4. This package is not affiliated with any anime studios or official licensors.

## License

This project is licensed under the MIT License.

## Contributing

To contribute new quotes or improvements, please submit a pull request to the following repository:

[miya3333](https://github.com/miya3333/anime-quotes-data)
