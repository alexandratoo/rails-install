# rails-install

## First, Intall RVM

```curl -sSL https://get.rvm.io | bash -s stable --rails```

#### Load RVM into your shell sessions as a function

```source ~/.rvm/scripts/rvm```

If you're using `fish` follow this guide: https://rvm.io/integration/fish

If you're using `zsh` follow this guide: https://rvm.io/integration/zsh

#### Test - should return `rvm is a function`, if not, rvm is not configured correctly!
```type rvm | head -n 1```

#### Configure gems:
```rvm user gemsets```

#### Install Ruby

* Depending on your Gemfile, you may need to install a specific version

Installs ruby version 2.2.5:

```rvm install 2.2.5```

Lists installed versions:

```rvm list```

Use a specific version:

```rvm use 2.2.5```

#### Intalling Rails

```gem install rails```

If you run into issues not being able to locate gems, set ```GEM_HOME="$HOME/.gems"```

#### Test
```rails -v```

#### Installing Bundler

```gem install bundler```

## Resources

* http://guides.rubyonrails.org/getting_started.html
* https://rubygems.org/
* http://bundler.io/
