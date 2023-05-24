# canxham

A practice exam generator for aspiring Canadian amateur radio operators, forked from VO1ZXZ's original work.

## ChangeLog

The following changes were made after forking VO1ZXZ's original work:
- ANSI color is added
- Only wrong answers are logged. It helps me to review the question and memorize the right answer.
- Download from ISED only when we don't have a local copy of the tests.
  You are still recommended to delete `amat_basic_quest_delim.txt` from time to time, in order to fetch the latest questions.
- Other tiny tweaks.

## Windows Users

Please either download VO1ZXZ's original [release](https://github.com/helpkilbananas/canxham/releases), or install Python 3
in console.

## Linux and Mac Users

Please run `python3 canxham.py` in console.


## Prerequisites

1. Python3.6 or higher
1. python-requests and colorama
   `pip3 install --user requests colorama`

## How to use this program

After installing Python and downloading this script, navigate to the extracted directory and run the following:

For a basic exam

```
python canxham.py basic
```

For an advanced exam

```
python canxham.py adv
```

Français:
Ajoutez '-mfr' au fin

```
python canxham.py adv -mfr
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
