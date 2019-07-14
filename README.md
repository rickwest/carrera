# Carrera
Turbo-charged `symfony new`! Rapid application creation for new Symfony projects.

![Carrera](./porsche-racecar.jpg?raw=true)

## About
Heavily inspired by Tighten's [Lambo](https://github.com/tightenco/lambo) and utilizing the [Symfony client](https://symfony.com/download), Carrera help's you get a new Symfony application up and running super fast. 

Sick of having to run those same commands every time you spin up a new project? Use Carrera to automate all the things!

---
## System Requirements
To use Carrera, you need to have PHP 7, Git and Composer installed on your machine. 

You'll also need the Symfony client - [Download here](https://symfony.com/download)

## Installation

```bash
composer global require rickwest/carrera
```

## Upgrading

```bash
composer global update rickwest/carrera
```

## Usage

Make sure `~/.config/composer/vendor/bin` is in your terminal's path.

```bash
carrera [project name]
```

This will `symfony new [project name]`, change into that directory, make an initial Git commit, start a web server and open the project in a web browser.

## What exactly does Carrera do?

- `symfony new $PROJECTNAME`
- `cd $PROJECTNAME`
- Initialize a git repo, add all of the files, and make an "Initial commit"
- Starts the [Symfony Local Web Server](https://symfony.com/doc/current/setup/symfony_server.html)
- Open's your project in a browser

---

## Bugs and Issues

If you encounter a problem or spot a mistake, or even if you would just like to make a suggestion, please open an issue. Pull requests are more than welcome too! 

## Contributing

- Fork it (https://github.com/yourname/yourproject/fork)
- Create your feature branch (git checkout -b feature/fooBar)
- Commit your changes (git commit -am 'Add some fooBar')
- Push to the branch (git push origin feature/fooBar)
- Create a new Pull Request

## Copyright and License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.