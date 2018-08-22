

# README

Its a Blog Project  

A simple CRUD for Ruby on Rails  


## To Change Authentication before running 

#### In File: "comments_controller.rb" under "controllers" folder

http_basic_authenticate_with name: "YOURNAME", password: "YOURPASSWORD", only: [:destroy]

#### In File: "posts_controller.rb" under "controllers" folder

http_basic_authenticate_with name: "YOURNAME", password: "YOURPASSWORD", except: [:index, :show]

## To Run

rails db:migrate  
rails s

## Examples

### Index page

![index-page](https://user-images.githubusercontent.com/38043621/44436534-b6bdf000-a583-11e8-8e5a-f803ef42ddb1.png)

### Show of Individual Post with Comments

![show-of-individual-post-with-comments](https://user-images.githubusercontent.com/38043621/44436568-ecfb6f80-a583-11e8-9fb4-3d1c445c20d5.png)

### To Create Blog

![create-blog](https://user-images.githubusercontent.com/38043621/44436489-75c5db80-a583-11e8-9fab-e0326c48fbf1.png)

### Edit Post Page

![edit-post](https://user-images.githubusercontent.com/38043621/44436606-2cc25700-a584-11e8-90b7-baaf81d18c30.png)
