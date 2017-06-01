# Starting a Rails Project

* <code>rails new <PROJECT_NAME> -d postgresql</code>
* cd into your project
* Think of what your model will have 🤔
* <code>rails g model <MODEL_NAME> <attribute_of_model>:<data_type></code>
* Apply db contraints eg. null: false
* in app/model/<MODEL_FILE>.rb apply validations <code>validates_presence_of :<ATTRIBUTE_NAME></code>
* Create Db <code>rails db:create db:migrate</code>
* Create controller for model
* <code>rails g controller <PLURALIZE_NAME_OF_MODEL> index show new edit</code>
* Update config/routes.rb
* Fill out controller method
* Update the views to display data given from controller
* Rinse and repeat
* CELEBRATE 🎉🎉🎉
