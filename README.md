

# Calculatr: Blockchain-Enhanced Calculator


**Calculatr** is an innovative Android calculator app that integrates blockchain technology to securely store and verify your calculation history. This unique approach ensures that every calculation you perform is immutable and traceable, providing an unprecedented level of transparency and security for users who require trust in their computational tasks.

## Features

- **Basic Calculator Functions**: Perform all standard arithmetic operations such as addition, subtraction, multiplication, and division.
- **Blockchain Integration**: Every calculation is recorded on a private blockchain to ensure data integrity and traceability.
- **Secure Calculation History**: View and verify past calculations with immutable records stored on the blockchain.
- **User-Friendly Interface**: Clean, intuitive design for easy navigation and usage.
- **Export and Share**: Export calculation history to share or backup.

## Installation

To install the **Calculatr** app on your Android device, follow these steps:

1. **Download the APK**: Get the latest release from the [Releases](https://github.com/yourusername/calculatr/releases) page.
2. **Enable Unknown Sources**: Go to `Settings` > `Security` and enable `Install from Unknown Sources`.
3. **Install the APK**: Open the downloaded APK file and follow the on-screen instructions to install the app.

Alternatively, you can clone the repository and build the app manually.

```bash
git clone https://github.com/yourusername/calculatr.git
cd calculatr
./gradlew build
```

## Usage

1. **Open the App**: Launch Calculatr from your app drawer.
2. **Perform Calculations**: Use the calculator interface to perform any arithmetic operations.
3. **View History**: Swipe left to access the history panel, where you can see all previous calculations.
4. **Verify Transactions**: Tap on any calculation to see its blockchain verification details.
5. **Export History**: Click the export button in the history panel to save your calculation history as a CSV file.

## Blockchain Integration

Calculatr leverages a private blockchain to store and verify calculations. Each time you perform a calculation, the result and operation are hashed and stored in a new block. This ensures that:

- **Data Integrity**: The calculation history cannot be altered or tampered with.
- **Traceability**: Each calculation can be traced back to its origin, providing a transparent history of all operations.
- **Security**: Blockchain technology protects your data from unauthorized access or modifications.

### How It Works

1. **Perform Calculation**: When you complete a calculation, it is added to a transaction.
2. **Create Block**: The transaction is bundled into a new block.
3. **Hash and Add to Chain**: The block is hashed and appended to the blockchain.
4. **Verification**: Each block includes a cryptographic hash of the previous block, forming a secure chain.

## Development

### Prerequisites

- Android Studio
- Java JDK 8+
- [Gradle](https://gradle.org/)

### Building from Source

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/calculatr.git
    ```

2. Open the project in Android Studio.
3. Sync the Gradle files and build the project.
4. Run the app on an emulator or connected device.

### Directory Structure

```plaintext
calculatr/
│
├── app/                    # Main application directory
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourusername/calculatr/    # Java source files
│   │   │   ├── res/         # Resources (layouts, drawables)
│   │   └── test/            # Unit tests
│   └── build.gradle         # Gradle build file for the app
├── blockchain/              # Blockchain-related modules
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourusername/blockchain/   # Blockchain source files
│   └── build.gradle         # Gradle build file for blockchain module
└── build.gradle             # Root Gradle build file
```

## Contributing

We welcome contributions from the community! If you would like to contribute to Calculatr, please follow these guidelines:

1. **Fork the Repository**: Create a personal fork of the project.
2. **Clone the Fork**: Clone your fork to your local machine.
3. **Create a Feature Branch**: Create a new branch for your feature or bugfix.
4. **Commit Your Changes**: Make your changes and commit them to your branch.
5. **Push to GitHub**: Push your branch to your forked repository.
6. **Submit a Pull Request**: Open a pull request to the main repository.


![alt text][logo]

[logo]: https://github.com/eloyzone/android-calculator/blob/master/app-screencapture.gif "Screen Capture of App"
