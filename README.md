# vscode-manager (vsm) [![Build Status](https://travis-ci.org/badersur/vscode-manager.svg?branch=master)](https://travis-ci.org/badersur/vscode-manager)

A script that downloads and updates VSCode *insiders* for Linux.
It downloads and extracts the app to the `~/Downloads` directory.

I don't like downloading apps using `apt-get` and I remember that VSCode
doesn't support auto updating on Linux but [this doesn't seem to be the
case anymore](https://code.visualstudio.com/docs/setup/linux)!

Anyways, I learned more about shell scripting while writing this script and I'll keep using it :)

I hope you'll find it useful!


## Usage

### One-liner

1. Open the terminal.

2. Run the script:
 ```bash
 curl https://raw.githubusercontent.com/badersur/vscode-manager/master/vsm | bash
 ```

### Grab the repo and run the script

1. Open the terminal.

2. Clone the repo using [git](https://git-scm.com/downloads):
 ```bash
 git clone https://github.com/badersur/vscode-manager
 ```

3. Change your current directory to repo's directory:
 ```bash
 cd vscode-manager
 ```

4. Execute the script `vsm`:
 ```bash
 ./vsm
 ```


## Issues & PRs?

Yes, please! You're more than welcome :)


## Thanks

1. [The Bad Tutorials](https://www.youtube.com/channel/UCEpe5DhhS0HYFBaCVsU2Iwg) for the awesome
 [Shell Scripting Tutorials](https://www.youtube.com/playlist?list=PL7B7FA4E693D8E790)

2. [ShellCheck](https://github.com/koalaman/shellcheck/)

3. [vscode-shellcheck](https://github.com/timonwong/vscode-shellcheck)


## License

MIT © [Bader Nasser Al-Hashmi](https://github.com/BaderSur)
