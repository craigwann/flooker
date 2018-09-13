Epicodus-1A:Desktop Guest$ rails new flooker

Epicodus-1A:Desktop Guest$ cd flooker/

Epicodus-1A:flooker Guest$ ls

Epicodus-1A:flooker Guest$ atom .

Epicodus-1A:flooker Guest$ git pair ws cw

Epicodus-1A:flooker Guest$ git remote add ws https://github.com/wvw999/flooker

Epicodus-1A:flooker Guest$ git remote add cw https://github.com/craigwann/flooker

Epicodus-1A:flooker Guest$ git add .

Epicodus-1A:flooker Guest$ git pair-commit -m "initial commit"

Epicodus-1A:flooker Guest$ git push ws master

Epicodus-1A:flooker Guest$ git bundle

Epicodus-1A:flooker Guest$ bundle

Epicodus-1A:flooker Guest$ bundle exec rails generate rspec:install

Epicodus-1A:flooker Guest$ rake db:create

Epicodus-1A:flooker Guest$ rails g devise:install

Epicodus-1A:flooker Guest$ rails g devise users

Epicodus-1A:flooker Guest$ rails g devise:views

Epicodus-1A:flooker Guest$ rails db:migrate

Epicodus-1A:flooker Guest$ rails active_storage:install

Epicodus-1A:flooker Guest$ rails db:migrate
