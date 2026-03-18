## Project Resources

- [OpenSGF](https://www.opensgf.org/): Join our weekly meetings!
- [Code of Conduct](https://www.opensgf.org/code-of-conduct): Please read before participating
- **Discord**: Click "Join" on [OpenSGF](https://www.opensgf.org/) website
- [Project Documentation](https://docs.opensgf.org/collection/good-dads-0SqBtE9EkS): Product Requirement Documents (PRDs)
- [Project Management](https://plane.sgf.dev/open-sgf/projects/b87b7a4a-10b8-40ee-808d-2ac930c0f46f/issues/): Claim a PRD and/or update PRD status here

## Project Setup

- [Install PHP](https://www.php.net/manual/en/install.php)
- [Install Composer](https://getcomposer.org/doc/00-intro.md)
- Install Docker
    - For Mac: [Docker Desktop](https://docs.docker.com/desktop/install/mac-install/) | [Orbstack](https://docs.orbstack.dev/quick-start#installation)
    - For Windows: [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
    - For Linux: [Docker Desktop](https://docs.docker.com/desktop/install/linux-install/)
- Navigate to the project directory and run `composer install`
- Duplicate the .env.example: `cp .env.example .env`
- Configure alias for sail: `alias sail='sh $([ -f sail ] && echo sail || echo vendor/bin/sail)'`
- Generate a new APP_KEY: `sail artisan key:generate`. This will automatically update the .env file for the APP_KEY value.
- Start the Docker containers: `sail up -d`
- Wait for the containers to start up. You can check the status of the containers with `sail ps`

