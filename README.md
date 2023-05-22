# FTP Server

This is a simple FTP server implementation in C. The server allows clients to perform basic file transfer operations such as login, upload, and download files.

## Features

- User authentication using login credentials
- File upload to the server
- File download from the server

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- C compiler (e.g., GCC)
- Socket programming libraries (specific libraries may vary based on the operating system)

### Installation

1. Clone the repository to your local machine:
2. Compile the server code using a C compiler. For example, using GCC:
3. Run the server executable:
4. The server should now be up and running, listening for client connections on a specified port.

## Usage

1. Connect to the server using an FTP client application or command-line FTP client.

2. Provide the necessary login credentials to authenticate yourself with the server.

3. Once logged in, you can perform the following operations:

- Upload a file to the server: Use the "upload" command followed by the local file path as the argument.
- Download a file from the server: Use the "download" command followed by the file name on the server as the argument.

4. To terminate the connection and exit the FTP session, use the "quit" or "exit" command.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Socket Programming in C](https://www.geeksforgeeks.org/socket-programming-cc/)
- [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/)
