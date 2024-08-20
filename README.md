# TinyURL Service

This project is a simple implementation of a URL shortening service, similar to TinyURL. The service allows users to shorten long URLs into shorter, more manageable URLs, and retrieve the original long URL using the shortened version.

## Features

- **Shorten URLs**: Convert a long URL into a short URL.
- **Retrieve Original URLs**: Retrieve the original URL from a shortened URL.
- **Unique Short URLs**: Generate unique short URLs using random alphanumeric characters.

## How It Works

The service generates a short URL by creating a unique key of 6 characters (composed of letters and digits). The long URL is mapped to this key, allowing it to be retrieved later. The shortened URL is then displayed with a base URL (e.g., `http://tinyurl.com/`), simulating the behavior of real URL shortening services.

### Example

- Long URL: `https://www.example.com/some/very/long/path`
- Short URL: `http://tinyurl.com/abc123`

## Getting Started

### Prerequisites

To run this project, you need to have Python installed.

### Running the Program

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ritikkumar19/tinyurl-service.git
   cd tinyurl-service
   ```

2. **Run the Program**:

   You can run the service using the following command:

   ```bash
   python tinyurl_service.py
   ```

3. **Use the Menu**:

   After running the program, you will see a menu with the following options:
   - Shorten a URL
   - Retrieve a URL
   - Exit

   Enter the corresponding number to perform the desired action.

### Project Structure

```
tinyurl-service/
│
├── README.md               # Project documentation
└── tinyurl_service.py      # Main Python script containing the TinyURL service
```

### Insights

This project provides a basic introduction to the principles of URL shortening services, including data mapping and random key generation. It’s a simple, yet powerful, demonstration of how URL shorteners work behind the scenes, making it a great learning tool for understanding string manipulation, dictionaries, and random generation in Python.

### Future Improvements

- Add a persistent storage mechanism (e.g., database) to store URLs across sessions.
- Implement analytics to track the number of times a shortened URL is accessed.
- Add custom short URL creation for users.

### Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.
