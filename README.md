Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.


config initializer : files read at the lauching of the server
modify :
 - our mail
 - regex: mail and passwor

config
 * envdev env
   - add config.act
   config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }
