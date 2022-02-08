# ANGULAR .htaccess Compilation
Compilation of Angular .htaccess files

## Navigation

- [Angular Internationalization](#internationalization)
- [Useful Links](#useful-links)

## Internationalization

The folder contains subdirectories for each locale. In my example there would be two subdirectories: **de** for German language and **en** for English.
The example .htaccess file automatically redirects the user to one of the directories, even when there is already an Angular routing attached to the link.

### Example

The user clicks on a link targeting your website: https://www.your-website-example.com/login.
Notice, that the required locale (**en** or **de**) is missing. Normally it would result in an 404 Error. But the .htaccess file redirects the user to the appropriate locale:
e.g. https://www.your-website-example.com/en/login, preserving the navigation routing.

### Installation:

Place the .htaccess file in the root directory.

## Useful Links

- [Angular .htaccess generator](https://julianpoemp.github.io/ngx-htaccess-generator/)