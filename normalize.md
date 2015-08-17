# Installation

Dockerfile: ruby:2.2.2


# Example

`gem install phony`

`ruby -e "require('phony'); puts Phony.normalize('1 (703) 451-5115')"`

Result should be: 17034515115

`ruby -e "require('phony'); puts Phony.format('41443643532')"`

Result should be: +41 44 364 35 32
