# My awesome Symfony 7 project

This is a symfony project for testing purposes and linters.

## Requirements

- PHP 8.1 or higher
- Composer
- Symfony CLI (optional, for convenience)

## Installation

### Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone git@github.com:jlbokass/myAwesomeBlog.git
cd your-project-name
```

### Install Composer Dependencies

```bash
composer install
```

### Create a .env File

```bash
cp .env .env.local
```

### Create the database and execute migrations

```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```

