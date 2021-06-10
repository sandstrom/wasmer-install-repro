## repro

```
# all of this is macOS big sur

# cd into this directory

brew install ruby-install
brew install direnv

ruby-install 2.6

cp ./dir-env.conf ~/.config/direnv/direnvrc

# cd in/out of this directory, to trigger direnv

direnv allow

# verify
which ruby
ruby --version
which gem

# should trigger the error
gem install wasmer --verbose
```
