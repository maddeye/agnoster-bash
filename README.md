# agnoster-bash
Agnoster Theme for Bash

agnoster's Theme - https://gist.github.com/3712874
A Powerline-inspired theme for BASH

Based on the work from Erik Selber
https://github.com/speedenator/agnoster-bash

# README

In order for this theme to render correctly, you will need a
[Powerline-patched font](https://gist.github.com/1595572).
I recommend: https://github.com/powerline/fonts.git
```
git clone https://github.com/powerline/fonts.git fonts
cd fonts
install.sh
```

In addition, I recommend the
[Solarized theme](https://github.com/altercation/solarized/) and, if you're
using it on Mac OS X, [iTerm 2](http://www.iterm2.com/) over Terminal.app -
it has significantly better color fidelity.

Install:

I recommend the following:
```
cd $HOME
mkdir -p .bash/themes/agnoster-bash
git clone https://github.com/maddeye/agnoster-bash.git .bash/themes/agnoster-bash
```

then add the following to your .bashrc:

```
export THEME=$HOME/.bash/themes/agnoster-bash/agnoster.bash
if [[ -f $THEME ]]; then
    export DEFAULT_USER=`whoami`
    source $THEME
fi
```