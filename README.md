# Inspectr

> Inspectr – Simplifying API and Webhook debugging!

**Inspectr** is a lightweight and efficient tool for reviewing, analyzing, and debugging API requests and webhook
events. Whether you're testing integrations, monitoring incoming requests, or troubleshooting payload issues, Inspectr
provides the insights you need.

<img src="https://raw.githubusercontent.com/thim81/inspectr/main/assets/inspectr-app.png" alt="Request Inspectr" width="80%">

<img src="https://raw.githubusercontent.com/thim81/inspectr/main/assets/inspectr-console.png" alt="Console Inspectr" width="80%">

## 🚀 Features

- **Inspect API Requests** – View headers, query parameters, request bodies, and response details.
- **Analyze Webhook Events** – Capture and review webhook payloads from third-party services.
- **Real-time Logging** – Monitor incoming requests as they happen.
- **Validation & Debugging** – Identify issues in request structures, missing parameters, and incorrect headers.
- **Multiple Deployment Options** – Use as an Express middleware, proxy, or standalone app.
- **Lightweight & Fast** – Built for performance with minimal dependencies.

# ⚙️ Components

Inspectr can be used in different ways, depending on your use case:

## 🔌 Request capturing

### 🔹 Express Middleware

Integrate **Inspectr** as middleware in an **Express.js** application to log and analyze incoming API requests and
webhook events. Ideal for adding inspection capabilities to existing Express Node.js applications.

### 🔹 Proxy Inspectr

Deploy **Inspectr** as an **HTTP proxy** to intercept requests and responses send to a backend service. Useful for
debugging API calls and webhook events without modifying your application.

## 🔍 Request inspections

### 🔹 Standalone App

Run **Inspectr** as an independent application that can be deployed in various environments:

- **Localhost** – Self-hosted for debugging API requests or webhook events directly on your machine.
- **VercelJS** – Cloud-hosted for easy access and seamless integration.

## 📖 Examples

### Capturing a Webhook Event

To test webhook logging, configure your third-party service to send events to:

https://your-instance.com/webhook

bash

Or send a test request manually:

```sh
curl -X POST http://localhost:3000/webhook -H "Content-Type: application/json" -d '{"event": "test"}'
```

Using as a Proxy
Point your API requests through the proxy for automatic request/response logging:

```sh

```

## 🤝 Contributing

We welcome contributions! Feel free to open an issue or submit a pull request.




