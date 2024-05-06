# Meteor Chat Application

## Introduction
This project utilizes the power of Meteor and MongoDB to provide a real-time chat platform. Users can set a nickname, send messages, and view messages from all users live. This README provides detailed instructions to get you started with this project, including how to handle split ZIP files using 7-Zip.

## Prerequisites
Before beginning, ensure you have the following installed:
- [Meteor](https://www.meteor.com/install) (latest version recommended)
- [7-Zip](https://www.7-zip.org/download.html) to handle split ZIP archives
- An IDE or code editor of your choice - This guide uses Visual Studio Code.

## Setup Instructions

### 1. Download the Split ZIP Files
Download all parts of the split ZIP archive for the project from the GitHub repository or the provided download links. Make sure to save all parts into the same folder on your computer.

### 2. Reassemble and Extract the ZIP File Using 7-Zip
To extract a split ZIP file using 7-Zip, follow these steps:

- **Locate the downloaded ZIP parts** in the folder where you saved them.
- **Right-click on the first part** (filename.zip.001) and choose '7-Zip' > 'Extract here' from the context menu. Ensure all parts (.001, .002, etc.) are in the same directory, and 7-Zip will automatically combine and extract them.

### 3. Open the Project in Visual Studio Code
- Launch Visual Studio Code.
- Go to `File` > `Open Folder...` and navigate to the extracted project folder. Select it and click `Open`.

### 4. Open a Terminal in VS Code
- Open a terminal within VS Code by navigating to `Terminal` > `New Terminal` from the top menu.

### 5. Install Required Libraries
Before running the project, install necessary Node libraries:
```bash
meteor npm install
```

## Running the Project
After setting up the environment and installing dependencies, you're ready to run the application:
```bash
meteor
```
You can now access the application by visiting [http://localhost:3000](http://localhost:3000) in your web browser.

## Conclusion
This Meteor Chat Application provides a dynamic platform for instant messaging. By following these steps, you can seamlessly set up and enjoy real-time communications. For further information or assistance, please refer to the Meteor documentation or reach out to the project maintainers.

Thank you for choosing the Meteor Chat Application!

---

