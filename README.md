# tf_packet


## vars

```
export token="<the_token>"
export TF_VAR_token=$token

export projectid=<the_projectid>
export TF_VAR_projectid=$projectid

export prefix=alvaro
export TF_VAR_prefix=$prefix

```

## build

```
brew install terraform

terraform fmt

terraform init

terraform plan

terraform apply
```


## rbenv

brew install rbenv

echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile

source ~/.bash_profile

rbenv init

## pre-req

rbenv

rbenv install 2.3.1

rbenv local 2.3.1

rbenv versions

gem install bundler

bundle install


## how to test

bundle exec kitchen converge

bundle exec kitchen verify

bundle exec kitchen destroy

## how to test all automated

bundle exec kitchen test

