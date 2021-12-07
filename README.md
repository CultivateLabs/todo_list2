# Setup

- Clone the repo:
```
git clone git@github.com:CultivateLabs/todo_list2.git
cd todo_list2/
```

- Install ruby-2.7.4 with whatever Ruby version manager you prefer

- Install gems:
```
bundle install
```

- Install JS dependencies:

If you don't already have yarn installed:
```
npm install --global yarn
```

Then:
```
yarn install
```

Database setup:
```
bin/rake db:create
bin/rake db:migrate
```

Run the app:
```
bin/rails s
```
