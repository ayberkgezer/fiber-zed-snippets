# Fiber Zed Snippets

**Fiber Zed Snippets** is a collection of productivity-boosting code snippets for [Fiber v2](https://github.com/gofiber/fiber) tailored for the [Zed IDE](https://zed.dev). With this extension, you can quickly scaffold common Fiber patterns, routes, middleware, and more, making your Go web development faster and less error-prone.

## Features

- **Up-to-date Fiber v2 snippets:** Includes setup, routing, middleware, error handling, static files, JWT, CORS, rate limiting, CRUD, MVC structure, REST API skeleton, and more.
- **Easy access:** Instantly insert snippets using Zed IDE’s snippet interface.
- **Parameterizable:** Most snippets include tab stops for quick variable and name customization.
- **Best practices:** Snippets reflect modern, idiomatic Fiber usage.

## Installation

### Method 1

1. Go to Extensions menu in Zed IDE
2. Search for "fiber-snippets"
3. Click "Install"

### Method 2
1. Clone this repo:
```
git clone https://github.com/ayberkgezer/fiber-zed-snippets.git
```
2. Go to Extensions menu in Zed IDE
3. Click "Install Dev Extension"
4. Select the folder you cloned

## Usage

1. In a Go file, type a snippet prefix (e.g. `fiber2-setup`, `fiber2-route`, `fiber2-json`, etc.) and press `Tab`.
2. The corresponding Fiber code block will be inserted, with placeholders for you to fill in.

## Snippet List

| Prefix                | Description                                 |
|-----------------------|---------------------------------------------|
| `fiber2-setup`        | Basic Fiber app setup                       |
| `fiber2-route`        | Route handler                               |
| `fiber2-group`        | Route group                                 |
| `fiber2-middleware`   | Custom middleware function                  |
| `fiber2-use`          | Global middleware                           |
| `fiber2-static`       | Serve static files                          |
| `fiber2-json`         | JSON response                               |
| `fiber2-error`        | Error handling                              |
| `fiber2-params`       | Read URL parameters                         |
| `fiber2-query`        | Query parameters                            |
| `fiber2-body`         | Parse request body                          |
| `fiber2-templates`    | Template engine setup                       |
| `fiber2-download`     | File download                               |
| `fiber2-upload`       | File upload                                 |
| `fiber2-cors`         | CORS middleware                             |
| `fiber2-limiter`      | Rate limiter middleware                     |
| `fiber2-jwt`          | JWT authentication                          |
| `fiber2-swagger`      | Swagger documentation                       |
| `fiber2-logger`       | Request logger middleware                   |
| `fiber2-cookies`      | Cookie handling                             |
| `fiber2-websocket`    | WebSocket endpoint                          |
| `fiber2-database`     | GORM database connection                    |
| `fiber2-model`        | GORM model definition                       |
| `fiber2-crud`         | CRUD operations                             |
| `fiber2-mvc`          | MVC structure skeleton                      |
| `fiber2-rest-api`     | REST API skeleton                           |

## Contributing

Contributions are welcome!

1. Fork the repository and create a new branch.
2. Add or improve snippets.
3. Open a pull request.

Suggestions, improvements, and new snippets are highly appreciated!

## License

[GNU GPL v3](./LICENSE)

---

**Author:**
Ayberk Gezer
<ayberkgezer@outlook.com>
