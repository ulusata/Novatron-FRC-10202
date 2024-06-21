### `docs/setup.md`

# Setting Up the Development Environment

Follow these instructions to set up your development environment for our FRC Robot Project.

## Prerequisites
- [Git](https://git-scm.com/) installed on your machine
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) version 11 or higher
- [Gradle](https://gradle.org/install/) installed
- An Integrated Development Environment (IDE) such as [IntelliJ IDEA](https://www.jetbrains.com/idea/) or [Visual Studio Code](https://code.visualstudio.com/)

## Cloning the Repository
1. Fork the repository on GitHub to your own account.
2. Clone your forked repository to your local machine:
   ```sh
   git clone https://github.com/your-username/repository-name.git
   cd repository-name

### IntelliJ IDEA
1. Open IntelliJ IDEA.
2. Select File > Open and choose the root directory of the cloned repository.
IntelliJ should automatically detect and set up the Gradle project. If not, select File > New > Project from Existing Sources and choose the build.gradle file.

### Visual Studio Code
1. Open Visual Studio Code.
2. Select File > Open Folder and choose the root directory of the cloned repository.
3. Install the necessary extensions for Java and Gradle support if prompted.
   
## Building the Project
* Open a terminal in the root directory of the repository.
* Run the following command to build the project:
```sh
  ./gradlew build
```

## Running Tests
To run the tests, use the following command:
  ```sh
./gradlew test
```

## Running Simulations
* Navigate to the simulations directory.
* Follow the instructions in the [README.md](url) file located in the simulations directory to set up and run simulations.
  
## Additional Resources
* Refer to the [README.md](https://github.com/ulusata/IronStags-FRC/blob/main/README.md) file for an overview of the project.
* Check the [CONTRIBUTING.md](https://github.com/ulusata/IronStags-FRC/blob/main/docs/CONTRIBUTING.md) file for guidelines on contributing to the project.
* If you encounter any issues during setup, please open an issue on GitHub.
