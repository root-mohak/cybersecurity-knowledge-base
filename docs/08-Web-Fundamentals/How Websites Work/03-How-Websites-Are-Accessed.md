# 🌐 How Websites Are Accessed

> Every time you open a website, several processes happen behind the scenes within milliseconds. Understanding this flow is essential for web development and web security. :contentReference[oaicite:0]{index=0}

---

# 📖 Overview

When you type a website address (URL) into your browser and press **Enter**, your browser communicates with different systems to retrieve and display the webpage.

Although it appears instant, multiple steps happen in sequence.

---

# 🔄 Website Access Flow

```
User
   │
   ▼
Enter URL
   │
   ▼
DNS Lookup
   │
   ▼
Find Server IP Address
   │
   ▼
Browser Sends Request
   │
   ▼
Server Processes Request
   │
   ▼
Server Sends Response
   │
   ▼
Browser Renders Webpage
```

---

# ⚙️ Step 1 — Enter a URL

A user types a website address into the browser.

Example:

```
https://www.google.com
```

The browser now needs to find where this website is located.

---

# ⚙️ Step 2 — DNS Lookup

Computers cannot understand names like:

```
google.com
```

They understand only IP addresses.

The browser asks the **Domain Name System (DNS)** to convert the domain name into an IP address. :contentReference[oaicite:1]{index=1}

---

# ⚙️ Step 3 — Find the Server

After DNS returns the IP address, the browser now knows where the website is hosted.

Example:

```
google.com
        ↓
142.xxx.xxx.xxx
```

The browser prepares to contact that server.

---

# ⚙️ Step 4 — Send an HTTP Request

The browser sends a request asking for the webpage.

Example:

```
GET /
```

The request travels across the Internet to the server.

---

# ⚙️ Step 5 — Server Processes the Request

The server:

- Receives the request
- Finds the requested webpage
- Runs application code if needed
- Retrieves data from databases
- Prepares a response

---

# ⚙️ Step 6 — Server Sends the Response

The server sends back resources such as:

- HTML
- CSS
- JavaScript
- Images
- Videos
- Fonts

These files travel back to the browser. :contentReference[oaicite:2]{index=2}

---

# ⚙️ Step 7 — Browser Renders the Website

The browser reads the files it receives.

It:

- Parses HTML
- Applies CSS styles
- Executes JavaScript
- Displays the final webpage

This entire process usually takes only a few milliseconds.

---

# 🧠 Real-Life Analogy

Imagine ordering a pizza.

1. You choose a restaurant.
2. You place your order.
3. The restaurant prepares the pizza.
4. The delivery driver brings it to your home.
5. You receive your pizza.

Similarly:

- You = Client
- Restaurant = Server
- Order = HTTP Request
- Pizza = HTTP Response

---

# 🌍 Example

You type:

```
https://www.youtube.com
```

The browser:

1. Finds YouTube's IP address.
2. Connects to YouTube's server.
3. Requests the homepage.
4. Receives HTML, CSS, JavaScript, and images.
5. Displays the YouTube homepage.

---

# 🎯 Why It Matters in Cybersecurity

Understanding how websites are accessed helps explain:

- SQL Injection
- Cross-Site Scripting (XSS)
- Broken Authentication
- Session Hijacking
- HTTP Request Manipulation
- API Security

Many attacks target one of these communication steps.

---

# 📝 Key Takeaways

- Opening a website involves multiple background steps.
- DNS converts domain names into IP addresses.
- Browsers send requests to servers.
- Servers process requests and return responses.
- Browsers render HTML, CSS, and JavaScript into webpages.
- This entire process happens in milliseconds
