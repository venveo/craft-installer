# Install Craft CMS from the command line

Install Craft CMS from a command line with composer. This tool is heavily inspired by the Laravel Installer.

## Requirements

- [Composer](https://getcomposer.org)

## Installation and Usage

1. Ensure that the `~/.composer/vendor/bin` is available in your terminal PATH.

	**Note**: my [Oh My ZSH](http://ohmyz.sh) profile has this line:

	`export PATH="/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/username/.composer/vendor/bin"`

	**Note**: make sure you change `username` above

2. Require `craft` globally by using this command:

	`composer global require "venveo/craft-installer=dev-master"`

3. Change to a new directory, such as `~/Sites`, and run `craft install mywebsite`.

## Credits

* [Jason McCallister](https://github.com/themccallister)

## About Venveo

Venveo is a Digital Marketing Agency for Building Materials Companies in Blacksburg, VA. Learn more about us on our website.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.