# 💻 Client vs Server

> The web follows a **client-server architecture**, where a client requests resources and a server processes the request and sends back a response. This communication is the foundation of every website and web application. :contentReference[oaicite:0]{index=0}

---

# 📖 What is a Client?

A **client** is a device or application that requests information from a server.

Most commonly, the client is a **web browser** such as:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

The client's job is to:
- Send requests
- Receive responses
- Display webpages
- Allow user interaction

---

# 📖 What is a Server?

A **server** is a computer that stores websites, applications, databases, and other resources.

The server's job is to:

- Receive client requests
- Process those requests
- Access databases if needed
- Send the requested data back to the client

A server usually runs 24/7 so users can access websites anytime.

---

# 🔄 How Client and Server Communicate

The communication follows a simple cycle:

```
Client  ─────── Request ───────▶  Server
Client  ◀────── Response ─────── Server
```

### Step-by-Step

1. User enters a website URL.
2. Browser (client) sends a request.
3. Server receives the request.
4. Server processes the request.
5. Server sends back HTML, CSS, JavaScript, images, or data.
6. Browser displays the webpage. :contentReference[oaicite:1]{index=1}

---

# 🧠 Real-Life Analogy

Imagine ordering food online.

### Client

You

### Server

Restaurant

### Request

Your food order

### Response

The prepared food delivered back to you

```
You
   │
   │ Order Food
   ▼
Restaurant
   │
   │ Prepare Food
   ▼
You Receive Food
```

The same process happens every time you open a website. :contentReference[oaicite:2]{index=2}

---

# 🌍 Real-World Example

When you visit:

```
https://www.google.com
```

The browser:

- Sends a request to Google's server.
- Google's server processes the request.
- The server sends back:
  - HTML
  - CSS
  - JavaScript
  - Images
- Your browser renders the Google homepage.

---

# 🔑 Key Concepts

## Client

- Requests information
- Runs in the user's device
- Usually a browser

## Server

- Stores website files
- Processes requests
- Sends responses
- Can communicate with databases

---

# 🎯 Why It Matters in Cybersecurity

Understanding the client-server model helps explain many web vulnerabilities, including:

- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Authentication vulnerabilities
- Session management issues
- API security

Every web attack begins with communication between a client and a server.

---

# 📝 Key Takeaways

- The client requests resources.
- The server provides resources.
- Websites use the request-response model.
- Browsers are common clients.
- Servers host websites and applications.
- Client-server communication is the foundation of the modern web.