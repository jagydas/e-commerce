# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

# Description
Build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

# Instruction
add a .env file as below
 DB_NAME= 'ecommerce_db';
 DB_USER= 'username';
 DB_PW= 'password';
 
 For running seedlist use command "npm run seed"
 Then run " npm install"
 Then run "node server.js"
 
 # Associations
 
You'll need to execute association methods on your Sequelize models to create the following relationships between them:

Product belongs to Category, as a category can have multiple products but a product can only belong to one category.

Category has many Product models.

Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.

Tag belongs to many Product models.
          
 
# WalkThrough Video
