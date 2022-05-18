# IGdm Messenger
Multi-platform Desktop application for INSTAGRAM DMs, built with electron

### It's a fork! 🍴
This is a **modified** version of Caprine that includes updated dependencies and other fixes. This enables Caprine to:
1) Run on newer OSs that use the clone3 syscall (e.g. Arch Linux, Fedora Rawhide, Ubuntu 22.04, etc.) (#1790)
2) Run on newer hardware (Apple Silicon / M1) (#1772)
3) Be more secure, as a lot of vulnerabilities were patched

Its sole purpose is to provide people with a more secure & up to date client until those issues can be fixed upstream.

### Packaging
TODO

## From the author

### View Website
[here](http://ifedapoolarewaju.github.io/igdm/)

### Preview

![Start a chat](docs/img/startchat.gif)

![Quote a message](docs/img/quotemessage.gif)

![View unfollowers](docs/img/unfollowers.gif)

### Local Development

To setup this project locally for development purposes please follow the following steps:

1. Ensure you Node.js installed. [See](https://nodejs.org/en/download/)

2. Clone this repo by running the command - `git clone https://github.com/ifedapoolarewaju/igdm.git`

3. Navigate to the directory where the repo is cloned to. (e.g `cd igdm`)

4. Run `npm install` to install all the dependencies.

5. Start the application locally by running `npm start`

That's it! :) Now you can have those pull requests rolling in! :D


## License

[The MIT License](LICENSE).
