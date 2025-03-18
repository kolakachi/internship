# Web Development Curriculum - Part 1: Internet Basics

## Introduction

Before diving into web development, it's essential to understand how the internet works. The internet is the foundation of all web applications, allowing users to access websites, communicate, and transfer data globally.

---

## 1. Understanding the Internet

The **internet** is a vast global network connecting computers and devices. It allows data exchange through interconnected servers and clients.

- The **World Wide Web (WWW)** is a collection of web pages accessible via the internet.
- **ISPs (Internet Service Providers)** offer access to the internet.

📌 **Further Reading:**

- [How the Internet Works (Cloudflare)](https://www.cloudflare.com/learning/network-layer/how-does-the-internet-work/)
- [Internet vs. WWW (GeeksForGeeks)](https://www.geeksforgeeks.org/difference-between-internet-and-www/)

---

## 2. Internet Service Providers (ISPs)

An **ISP (Internet Service Provider)** is a company that provides internet access to users.

📌 **Further Reading:**

- [What is an ISP? (Cisco)](https://www.cisco.com/c/en/us/support/docs/ip/internet-protocol-ip/14179-how-inet-works.html)

---

## 3. IP Addresses, Domains, and URLs

Every device on the internet has a unique **IP (Internet Protocol) address**, which allows communication.

### Key Concepts:

- **IP Addresses**: Numeric labels (e.g., `192.168.1.1`) assigned to devices.
- **Domain Names**: Human-friendly names (`google.com`) that map to IPs.
- **URLs (Uniform Resource Locators)**: Complete web addresses (`https://www.example.com/home`).

📌 **Further Reading:**

- [What is an IP Address? (Kaspersky)](https://www.kaspersky.com/resource-center/definitions/what-is-an-ip-address)
- [How Domain Names Work (ICANN)](https://www.icann.org/resources/pages/what-2012-02-25-en)

---

## 4. HTTP and HTTPS

Websites use **HTTP (Hypertext Transfer Protocol)** to send and receive data. **HTTPS** is the secure version.

| Feature  | HTTP                | HTTPS                              |
| -------- | ------------------- | ---------------------------------- |
| Security | Unencrypted         | Encrypted with SSL/TLS             |
| Speed    | Faster              | Slightly slower due to encryption  |
| Use Case | Non-sensitive sites | Banking, e-commerce, secure logins |

📌 **Further Reading:**

- [HTTP vs. HTTPS (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

---

## 5. Web Browsers and Developer Tools

A **web browser** is an application that retrieves and displays web content.

### Popular Browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Apple Safari

### Developer Tools:

Modern browsers include **developer tools (DevTools)** for debugging, inspecting, and optimizing websites.

📌 **Further Reading:**

- [Introduction to DevTools (Google)](https://developer.chrome.com/docs/devtools/)

---

## 6. DNS (Domain Name System)

DNS translates human-friendly **domain names** into machine-readable **IP addresses**.

📌 **Further Reading:**

- [How DNS Works (Cloudflare)](https://www.cloudflare.com/learning/dns/what-is-dns/)

---

## 7. Client-Server Architecture

The **Client-Server model** is how web applications operate.

### How It Works:

1. A **client** (browser) sends a request to a **server**.
2. The **server** processes the request and returns a response.
3. The client displays the content.

📌 **Further Reading:**

- [Client-Server Model Explained (RedHat)](https://www.redhat.com/en/topics/cloud-computing/what-is-client-server-model)

---

## 8. HTML & CSS Fundamentals

Web pages are built using:

- **HTML (HyperText Markup Language)** – Defines page structure.
- **CSS (Cascading Style Sheets)** – Styles and layouts the page.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>My First Web Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
      }
      h1 {
        color: navy;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to Web Development!</h1>
    <p>This is a simple HTML & CSS example.</p>
  </body>
</html>
```

📌 **Further Reading:**

- [HTML Tutorial (W3Schools)](https://www.w3schools.com/html/)
- [CSS Basics (MDN)](https://developer.mozilla.org/en-US/docs/Learn/CSS)

---

## Conclusion

Understanding the **internet's fundamentals** is key to becoming a skilled web developer. In this guide, we explored:
✅ The difference between the Internet and the WWW
✅ How ISPs, IPs, and domain names work
✅ HTTP vs. HTTPS and web security
✅ The role of DNS and Client-Server architecture
✅ The basics of HTML & CSS

For deeper learning, explore the links provided. Happy coding! 🎉
