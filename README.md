# e-commerce-backend
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. The goal of this project was to understand the fundamental architecture of these platforms.

The E-Commerce Backend is a REST API for an internet retail website. The API is built onto an Express.js server that uses Sequelize to interact with a MySQL database. Sequelize is a promise-based Node.js ORM(Object Relation Mapping) for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

This E-Commerce backend has the API routes that point to each of the standard CRUD operations for each data group. The routes can be used to:

Create categories, products, tags
View categories, products, tags
Establish associations between the different entities
Update categories, products, & tags
Delete entries from the database
All that's missing to make this a complete E-Commerce website is a simple front-end application that makes calls to the API routes that are already built-in. If that's too much, simply try making requests to the API routes from your browser to the see the raw data that's returned.

