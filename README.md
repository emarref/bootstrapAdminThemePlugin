## No Longer Maintained

This repository is no longer maintained. The bootstrap version used is 2.0.2, which is very different in functionality to current Bootstrap releases. If you would like to take over this repository, do get in touch.

---

## Installation

Add this repository as a git submodule, or just place the bootstrapAdminThemePlugin folder in your project's plugins folder.

    git submodule add git://github.com/malcoholm/bootstrapAdminThemePlugin.git plugins/bootstrapAdminThemePlugin
    git submodule update --init

Enable the plugin in your ProjectConfiguration class.

## Usage

Enable the plugin on your module by setting the theme on creation of the admin generator module.

    ./symfony doctrine:generate-admin --theme=bootstrap backend ModelName

or in generator.yml if you've already created your module

    generator:
      param:
        theme:                 bootstrap

## License

bootstrapAdminThemePlugin is licensed under the MIT License.
