# gitSwitch
A tool for switching git profiles. This is useful if you have multiple git profiles, e.g. a personal profile and a work/professional profile.

### How to use gitSwitch?
1. Clone the repository: `git clone https://github.com/nokaa/gitSwitch`
2. Make the script executable by running the following command: `chmod +x /path/to/gitSwitch/gitSwitch`
3. This step is optional, but I would recommend moving gitSwitch somewhere in your path.
4. Create the folder `~/.config/git` and place your .gitconfig files in this directory with whatever name you like.
For example, I might have `~/.config/git/nokaa1` and `~/.config/git/nokaa2`. If I'm currently using the `nokaa1` profile and I want to switch to `nokaa2`, I run `gitSwitch nokaa2`, and gitSwitch will switch the profile. If you misspell the name of a profile, gitSwitch will print an error message.

### Usage
```
USAGE:
    gitSwitch <NAME>         Switch the current git profile with <NAME>
    gitSwitch help           Print this help message
```
