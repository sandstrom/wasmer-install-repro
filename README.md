## repro

```
# all of this is macOS big sur

brew install ruby-install
ruby-install 2.6

direnv allow

# verify with `which ruby`, `ruby --version` and `which gem`

# should trigger the error
gem install wasmer --verbose
```
