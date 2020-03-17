# ignore_it

This extension helps you to automatically ignore files and folders in your project workspace.

## Features

* The key should be `ignore_it.array`, while the value should be an array of files or folders you wish to ignore.
* If any of the files or foilders specified in the array exists in your project directory, `ignore_it` extension will add it to the `.gitignore` file.
* If `.gitigore` file does not exist in your project directory, `ignore_it` extension will create a `.gitignore` file and fill in the files you're to ignore.
* The `.gitignore` content will be the files in your project directory that corresponds to the `ignore_it.array`
* You can manually add other files to the `.gitignore` file. New files are always appended to the existing ones.
* If `.env` file is part of the files in your directory, `ignore_it` extension will create a `.env.example` file and fill it with the the contents of your .env file. Only variables are filled in, values are left behind. The `.env` and `.env.example` files will always be in sync.

## Requirements

This extension works when you're working in a git repository on VSCODE.

## Extension Settings

This extension requires that `ignore_it.array` key be added to your VSCODE `settings.json` file and value should be an array of files you wish to automatically add to `.gitignore` file in all your project (if the files or folders exist in your project). See example below
```json
"ignore_it.array": [".env", "node_modules", "coverage"]
```

## Known Issues

No known issues

## Release Notes

Initial release

### 1.0.0

### Contact

* [LinkedIn](https://www.linkedin.com/in/marcdomain)
* [GitHub](https://www.github.com/marcdomain)
* [Twitter](https://www.twitter.com/marcdomain)

**Enjoy!**
