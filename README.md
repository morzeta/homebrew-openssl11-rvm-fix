# homebrew-openssl11-rvm-fix
Fix/workaround for using RVM with Ruby as openssl@1.1 is no longer available in Homebrew.


Then users install from it with:

```bash
brew tap morzeta/openssl11-rvm-fix
brew install openssl@1.1
```

The version that is used is 1.1.1zh from https://github.com/kzalewski/openssl-1.1.1

You can change the version by modifiying the formula. Just don't forget to edit the checksum too.
