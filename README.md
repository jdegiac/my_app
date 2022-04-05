# README

# ruby_on_rails

# In order to create your own program using ruby on rails in collaboration with HTML and CSStailwind 
# you need to run the following command in your command line

# I would reccommend making sure that you have the latest versions of ruby and rails and have tailwindcss (or other front end styling) instawlled
# If you dont have ruby or rails it can be installed using homebrew

To check versions of ruby, rails, and tailwind use these commands in your terminal:
#1) ruby -v
#2) rails -v 
#3) tailwind can be installed using npm (use the link below to follow documentation)
    https://tailwindcss.com/docs/installation

To create your first ruby on rails program run these commands:
#1) gem update rails --pre                                                  (updates rails gems with prerelease flag which may not be necessary)
#2) rails new my_app database=postgresql --css tailwind cd my_app           (configures the my_app folder with postgresql and CSStailwind)
#3) cd my_app
#4) rails db create                                                         (creates the database)
#5) code .                                                                  (opens the folder in VSCode if you have this command configured)
#6) bundle
#7) rails g scaffold task title description:text due_at:datetime deleted_at:datetime state:integer  (scaffold generator function to help 
#8) rails g scaffold user name email
#9) rails db:migrate
#10) bin/dev            (to run puma server, usually you run server with 'rails s', i had difficulty with tailwind styling using rails s)

Open on Localhost:3000

For more information check this website:
https://guides.rubyonrails.org/v3.2/getting_started.html

