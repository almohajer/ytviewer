# YTViewer

**YTViewer** is simple YouTube views bot.

## Content

- [Content](#content)
- [Features](#features)
- [Installation](#installation)
  - [Windows](#windows)
  - [Unix](#unix)
- [Usage](#usage)
- [Documentation](#documentation)
  - [Required arguments](#required-arguments)
  - [Optional arguments](#optional-arguments)
- [Disclaimer](#disclaimer)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Features

* Multi-threaded.
* Support for multiple URLs.
* Support for ChromeDriver and GeckoDriver.
* Headless mode.
* Slow start mode for older machines.
* Configurable view duration.
* IP and User agent rotation.
* Referer spoofing.
* Debug mode.

## Installation

### Windows

* Install [Git](https://git-scm.com/download/win).
* Install [Python](https://www.python.org/downloads/).
* Install [Google Chrome](https://www.google.com/chrome/).
<br>Or
<br>Install [Firefox](https://www.mozilla.org/firefox/new/).
* Run following command in the command prompt:
```
git clone https://gitlab.com/DeBos/ytviewer.git
```

### Unix

* Run following commands in the terminal:
```
curl -fs https://gitlab.com/DeBos/mpt/raw/master/mpt.sh | sh -s install "git python"
git clone https://gitlab.com/DeBos/ytviewer.git
```

## Usage

`python main.py ARGUMENTS`

## Documentation

### Required arguments

| Argument       | Description                  |
| :------------- | :--------------------------- |
| -u, --url URL  | Sets url of video.           |
| -u, --url PATH | Sets path to file with urls. |

### Optional arguments

| Argument                         | Description                              | Default value                  |
| :------------------------------- | :--------------------------------------- | :----------------------------- |
| -h, --help                       | Shows help message and exits.            |                                |
| -t, --threads N                  | Sets number of threads.                  | 15                             |
| -D, --driver <chrome \| firefox> | Sets webdriver.                          | chrome                         |
| -H, --headless                   | Enables headless mode.                   | False                          |
| -s, --slow-start                 | Enables slow start mode.                 | False                          |
| -du, --duration N                | Sets duration of view in seconds.        | Video duration.                |
| -p, --proxies PATH               | Sets path to file with proxies.          | Proxies list from internet.    |
| -U, --user-agent AGENT           | Sets user agent.                         | Randomly generated user agent. |
| -U, --user-agent PATH            | Sets path to file with user agents.      |                                |
| -R, --referer REFERER            | Sets referer.                            | https://google.com             |
| -R, --referer PATH               | Sets path to file with referer.          |                                |
| -v, --verbose                    | Enables verbose mode.                    |                                |
| -d, --debug <warning \| error>   | Enables debug mode.                      | False                          |
| -r, --refresh N                  | Sets refresh rate for logger in seconds. | 1.0                            |

## Disclaimer

**YTViewer** was created for educational purposes and I'm not taking responsibility for any of your actions.

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos](https://gitlab.com/DeBos)

## Contact

* Telegram: [@DeBos99](https://t.me/DeBos99)
* Instagram: [@DeBos98](https://www.instagram.com/DeBos98)
* Reddit: [DeBos99](https://www.reddit.com/user/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
