# Starting A Rails Project

* <code>rails new <PROJECT_NAME> -d postgresql</code>
* Think of what your model will have 🤔
* <code>rails g model <MODEL_NAME> <attribute_of_model>:<data_type></code>
* Apply Model validation eg. null :false
* Create Db <code>rails db:create db:migrate</code>
* Create controller for model
* <code>rails g controller <PLURALIZE_NAME_OF_MODEL> index show new edit</code>
* Update config/routes.rb
* Fill out controller method
* Update the views to display data given from controller
* CELEBRATE 🎉🎉🎉
