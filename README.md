# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

**Description**

This is a back end e-commerce website that uses the latest technologies to interact with a MySQL database. It allows users to perform CRUD operations on categories, products, and tags.

**Table of Contents**

* [Installation](https://chat.openai.com/chat#installation)
* [Usage](https://chat.openai.com/chat#usage)
* [Walkthrough Video](https://chat.openai.com/chat#walkthrough-video)
* [Technologies Used](https://chat.openai.com/chat#technologies-used)
* [Contributing](https://chat.openai.com/chat#contributing)
* [Questions](https://chat.openai.com/chat#questions)

**Installation**

To use this application, you will need to perform the following steps:

1. Clone the repository to your local machine using
   ```
   git clone git@github.com:monicapong/eCommerceBackEnd.git
   ```
2. Navigate to the root directory of the project and run **npm install** to install the necessary dependencies.
3. Create an environment variable file **.env** and add the following:

```
DB_NAME='ecommerce_db' 
DB_USER='<your-mysql-username>' 
DB_PW='<your-mysql-password>' 

```

Replace **`<your-mysql-username>`** and **`<your-mysql-password>`** with your actual MySQL username and password.

4. Connect to MySQL and run the **schema.sql** file to create the database.
5. Seed the database by running  **npm run seed** .
6. Start the server by running  **npm start** .

**Usage**

Once you have completed the installation steps, you can use a tool like [Insomnia](https://insomnia.rest/) to test the API routes.

The following routes are available:

**Categories**

* GET all categories: **GET /api/categories**
* GET a single category: **GET /api/categories/:id**
* POST a new category: **POST /api/categories**
* PUT update a category: **PUT /api/categories/:id**
* DELETE a category: **DELETE /api/categories/:id**

**Products**

* GET all products: **GET /api/products**
* GET a single product: **GET /api/products/:id**
* POST a new product: **POST /api/products**
* PUT update a product: **PUT /api/products/:id**
* DELETE a product: **DELETE /api/products/:id**

**Tags**

* GET all tags: **GET /api/tags**
* GET a single tag: **GET /api/tags/:id**
* POST a new tag: **POST /api/tags**
* PUT update a tag: **PUT /api/tags/:id**
* DELETE a tag: **DELETE /api/tags/:id**

**Walkthrough Video**

Please refer to [this walkthrough video](https://drive.google.com/file/d/12wSdiF4DHoPdlD7p-oiiKRIVZHia4gVZ/view?usp=sharing) to see the functionality of the application.

**Technologies Used**

* Node.js
* MySQL
* Sequelize
* Express.js
* dotenv

**Contributing**

If you would like to contribute to this project, please open an issue or a pull request and provide a detailed description of your changes.

**Questions**

If you have any questions about the project, please feel free to contact me through my [GitHub](https://github.com/monicapong)
