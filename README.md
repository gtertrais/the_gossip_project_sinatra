#The Gossip Project - Sinatra



>Created on 29/07/2019 by Gaspard Tertrais.



**Note aux correcteurs**
I made the project until 2.7, I created an edit page but unable to modify the gossip afterwards.
to run a local server, in the folder, enter in terminal "shotgun -p 4567", then go to the navigator at the address "http://localhost:4567/"
Voila!

## Content


- **db/** : Databases 
- **lib/** : Views, controller and model
- **Gemfile, Gemfile.lock** : Gem and dependencies. See below.



## Classes



Provides methods and variables to organize class process and its different phases.



- # initialize



## Gemfile



```



ruby '2.5.1'
source 'https://rubygems.org'
gem 'pry'
gem 'rspec'
gem 'sinatra'
gem 'shotgun'
gem 'csv'
