# blog
Web Development project
Build a personal blog. The blog will display blog posts as a list. Each blog post will belong to a category. Visitors may view all posts in the home page or select a category in order to view the posts of this category. Clicking on a post's title, the visitor will view the full text of the blog post.
log owners will be able to login and publish new posts, update or delete existing ones. They will also be able to maintain the settings of the blog (title, posts per page, allow comments) and post categories. Statistics data should be displayed about the impressions of each post.
Visitors will be able to add comments to any blog post
# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
.env configuration
php artisan migrate –seed (important)
php artisan serve
