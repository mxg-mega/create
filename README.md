# Create Script

![License](https://img.shields.io/github/license/mxg-mega/createscript)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Platform](https://img.shields.io/badge/platform-Linux-blue)

A simple and powerful Bash script that creates files, makes them executable, and opens them in your favorite editor. Customize the script with various options to suit your needs, including support for popular editors like Vim, VS Code, Emacs, Nano, and Sublime Text.

## Features

- Create multiple files at once.
- Make files executable with a simple flag.
- Open files in your favorite editor using a quick command.
- Lightweight and easy to use.

## Installation

### Method 1: Clone the Repository

```bash
git clone https://github.com/mxg-mega/create.git
cd create
sudo chmod +x create
```

Add the script to your PATH:
```
sudo mv create /usr/local/bin/create
```

### Method 2: Install via apt (Coming Soon)

We are working on making the script available via apt. Please check back soon or contribute to this process by raising an issue or pull request!

## Usage

### Basic Usage
Create a file:
```
create filename.txt
```

Make a file executable:
```
create -x script.sh
```

Open in a specific editor:
```
create -v file.txt  # Opens in VS Code
create -e file.txt  # Opens in Emacs
create -n file.txt  # Opens in Nano
create -s file.txt  # Opens in Sublime Text
```

### Help Command

To display all available options:
```
create -h
```

## Contributing

We welcome contributions from the community! Here’s how you can get involved:
 1. Fork the Repository
 2. Create a new branch (git checkout -b feature-branch).
 3. Make your changes and commit (git commit -am 'Add new feature').
 4. Push to the branch (git push origin feature-branch).
 5. Open a pull request.

Please include a clear description of the changes and ensure that your code adheres to the project's coding style.

## Contributor File
We maintain a [CONTRIBUTORS.md](CONTRIBUTORS.md) file to acknowledge those who contribute to the project. Your contributions are valued and will be credited accordingly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Roadmap

- [x] Create and open files in specified editors.
- [ ] Add more editors as options.
- [ ] Make the script available via apt package manager.
- [ ] Internationalization and localization support.

## Support

For any questions, issues, or feature requests, please open an issue on GitHub or contact us at [muhammadmasanawa75@gmail.com].

## Acknowledgments

- Inspired by the need for a quick and easy file creation and editing script.
- Thanks to all contributors who make this project better!
