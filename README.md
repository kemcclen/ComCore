# ComCore

## Description:

Back end of an e-commerce database configuring a working Express.js API to use Sequelize to interact with a MySQL database.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Contributions](#contributions)
- [Links](#links)
- [License](#license)

## Installation:
1. Clone this repository to your local machine.

2. Install the required dependencies using the following command:

    npm install inquirer@8.2.4 mysql2 sequelize

3. Set up your MySQL database by executing the schema.sql file to create the necessary tables.

4. (Optional) Run the seeds.sql file to pre-populate your database with sample data.

5. Update the database credentials in the const db connection with your own MySQL credentials.

6. Start the application by running the following command:

    node server.js

7.  Using insomnia or your browser, view:

- localhost:3001/api/categories
- localhost:3001/api/products
- localhost:3001/api/tags



## Usage:

After you have followed the steps in [Installation](#installation):

**Interface**: ComCore runs in the browser or applications like Insomnia that are designed to design, debug or test API's. 

**Errors**: If errors occur, you will see a "Wroung Route!" message. Please check that you have used:
- localhost:3001/api/categories
- localhost:3001/api/products
- localhost:3001/api/tags

**id search**: if you are looking for a specific category, product or tag, add the id number to the end of your search. For example:
- localhost:3001/api/categories/1
- localhost:3001/api/products/3
- localhost:3001/api/tags/4


## Demonstration:

1. **Categories** localhost:3001/api/categories
![categories](/assets/categories.png)

2. **Products** localhost:3001/api/products
![products](/assets/products.png)

3. **Tags** localhost:3001/api/tags
![tags](/assets/tags)

3. **id Search** localhost:3001/api/tags/4
Add the id number of the category, product or tag you are looking for to your endpoint. For example, 4 in this case.
![idsearch](/assets/idsearch.png)





https://github.com/kemcclen/ComCore/assets/123762040/159e8cd6-b76a-4731-9bcc-090a0298143a




## Contributions: 

Contributions to ComCore are welcome! If you have any improvements, bug fixes, or new features to add, feel free to submit a pull request.

To contribute to ComCore, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes in the new branch.
4. Commit your changes, providing a descriptive commit message.
5. Push your branch to your forked repository.
6. Open a pull request against the main repository.
7. Provide a clear and concise description of your changes in the pull request.
8. Submit the pull request and wait for feedback or further instructions.

Please note that by submitting a pull request, you agree to allow the project maintainers to license your work under the project's existing license.

Thank you for considering contributing to ComCore. Your contributions are highly appreciated!

## Links: 
- Repository: https://github.com/kemcclen/ComCore

## License:
WorkFlow is licensed under the [MIT License](https://opensource.org/license/mit/).

_The MIT License is a permissive open-source license that allows you to use, modify, and distribute the project for both commercial and non-commercial purposes. It provides you with the freedom to customize the application to suit your needs._

_By contributing to ComCore, you agree that your contributions will be licensed under the same MIT License. This ensures that the project remains open-source and accessible to the community._
