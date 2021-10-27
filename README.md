# lenne.Tech homebrew formulae
Formulas for installing non-official [homebrew](https://brew.sh/) packages.

## sshpass
[sshpass](http://manpages.ubuntu.com/manpages/trusty/man1/sshpass.1.html) is a noninteractive ssh password provider.  

### brew
```
brew install https://raw.githubusercontent.com/lenneTech/homebrew-formulas/main/formulas/sshpass.rb
```  
Inspired by https://github.com/kadwanev/bigboybrew/blob/master/Library/Formula/sshpass.rb

### Hints
If an error occurs during the installation of sshpass because `gsed` is expected instead of `sed`:

    cd /usr/local/Library/ENV/4.3
    ln -s /usr/local/bin/gsed gsed
