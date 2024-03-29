# Secrets
This is a simple password generator written in Python. The bulk of the code is for the UI considering the simplicity of generating a random string in Python. For the UI it uses Tkinter with my custom theme [minimal-tkinter](https://github.com/tywil04/minimal-tkinter). The actual random number generation uses `random.SecureRandom()` which internally uses OS provided randomness that is classed as cryptographically secure.

**WARNING**: Do not actually use to generate passwords. This program has not been tested at all for its overall security.

# Screenshots:
!["Secrets Application"](/secrets.png)

# Usage
Run `password.py`

## Program Settings:
- `Has Letters`: Generate a password that contains letters (a-z, A-Z)
- `Has Digits`: Generates a password that contains numbers (0-9)
- `Has Punctuation`: Generates a password that contains all ASCII punctuation
- `Number of characters`: Changes number of characters in the output (Who would have thought?)

Alongside the settings, there are 2 extra buttons `Copy` and `Save` - they both do what they say on the tin. Copy copies the result into your clipboard, Save prompts you to save a file somewhere on your computer.

## Generate Password:
Click the button labled `Generate Password`.
