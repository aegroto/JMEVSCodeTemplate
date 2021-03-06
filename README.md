# JME VS Code template

This repository contains a boilerplate for jMonkeyEngine projects to be used as a workspace in Visual Studio Code.
Main features:
- Gradle build file
- Dedicated assets folder
- Automated tasks for build

## Gradle

The included gradle build file contains easily editable environment variables, making easy to switch jME's version and repository.

## Assets

Every asset should be placed inside the "assets" folder. It is configured as a subproject to be packed in the final jar while building. 

## Tasks

The boilerplate contains some tasks to automate the most common gradle operations during development on jME:
- gradle build
- gradle clean
- gradle run
- gradle clean and run

## Support

If you need any support about this boilerplate open an issue or send a mail at aegroto@protonmail.com

## License

Every content in this repository is released under GPLv3:https://www.gnu.org/licenses/gpl-3.0.en.html