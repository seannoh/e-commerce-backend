# Employee Tracker

[![MIT License](https://img.shields.io/badge/License-MIT-green)](#license)

The database and API back end for an e-commerce site built using Node.js, Express.js, MySQL and Sequelize.

## Description 

This project is the back end for an e-commerce site built in Node. It uses Express to create a functional API that performs CRUD operations on a database. The database and its models and associations are created with MySQL and Sequelize.

## Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Sequelize](https://sequelize.org/)


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Contributing](#contributing)

## Installation
  1. Upload all files or fork this repository to a server with a Node.js runtime environment and a MySQL Server. 
  2. Run `npm -i` from the root directory to install dependencies for this app. 
  3. Create a `.env` file in the root directory with this format: 
      ```
      DB_NAME=ecommerce_db
      DB_USER=(your user)
      DB_PASSWORD=(your password)
      ```
  4. From the root directory, open MySQL Shell and run `source ./db/schema.sql;` to create the database.
      - Optionally run `npm run seed` to populate the database with sample data.
  5. Run `npm start` to start the server.
  
## Usage 
Run `npm start` to start the server.

Access API endpoints to view, add, update, and delete categories, products and tags.

Categories:

![categories-preview](./assets/categories-preview.gif)

Products:

![products-preview](./assets/products-preview.gif)

Tags:

![tags-preview](./assets/tags-preview.gif)

Link to walkthrough [video](https://drive.google.com/file/d/1x8rs_f5j-kVDjvlGiVyZG9n4xVi_V_u3/view?usp=sharing)

## Credits
This application was built with the support of the resources and staff of the UCB Full Stack Full Time Coding Bootcamp Summer 2022. 


## License
<details>
  <summary><b>MIT License</b></summary>

```
MIT License

Copyright (c) 2022 seannoh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
      
</details>

## Contributing
This project isn't currently acccepting contributions.

## Questions
- View my Github [profile](https://github.com/seannoh)
- Contact me at my [email](mailto:seanoh@ucsb.edu)





