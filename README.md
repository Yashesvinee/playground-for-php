# Appwrite's Php Playground 🎮

Appwrite playground is a simple way to explore the Appwrite API & Appwrite Php SDK. Use the source code of this repository to learn how to use the different Appwrite Php SDK features.

[![Php Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://www.php-fig.org/psr/psr-12/)

**Work in progress**

## Get Started

This playground doesn't include any Php best practices but rather intended to show some of the most simple examples and use cases of using the Appwrite API in your Php application and server.

## System Requirements
* A system with Php installed.
* You have readily available AppWrite running instance (localhost in most cases).
* Create a project in AppWrite instance using console.
* Generate a secret key in the AppWrite instance using console.

### Installation
1. Clone this repository.
2. cd into to repository.
3. Open the app.php file found in the root of the cloned repository.
4. Copy the project_id, endpoint, secret key from your Appwrite Console.
4. Update project_id, endpoint, secret key by copied from the console in global.inc.php file where stated.
5. Install dependencies using  composer (`composer install`).
5. Execute the command `php app.php`
6. You will see the JSON response in the console.

### API Covered in Playground.
* Create Collection
* List Collection
* Add Document
* List Documents
* Upload File
* Create User
* List User

## Contributing

All code contributions - including those of people having commit access - must go through a pull request and approved by a core developer before being merged. This is to ensure proper review of all the code.

We truly ❤️ pull requests! If you wish to help, you can learn more about how you can contribute to this project in the [contribution guide](https://github.com/appwrite/appwrite/blob/master/CONTRIBUTING.md).

## Security

For security issues, kindly email us [security@appwrite.io](mailto:security@appwrite.io) instead of posting a public issue in GitHub.

## Follow Us

Join our growing community around the world! Follow us on [Twitter](https://twitter.com/appwrite_io), [Facebook Page](https://www.facebook.com/appwrite.io), [Facebook Group](https://www.facebook.com/groups/appwrite.developers/) or join our Discord Server [Discord community](https://discord.gg/GSeTUeA) for more help, ideas and discussions.
