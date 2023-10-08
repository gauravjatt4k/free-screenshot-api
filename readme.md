#
### 🌐 Welcome to the Screenshot API - Your Free & User-Friendly Solution!

### 🚀 Introduction
Welcome to the Screenshot API, your gateway to effortlessly capture web page screenshots. Whether you're a seasoned developer or just starting out, our API is designed with you in mind. It's perfect for testing, experimenting, and integrating screenshot capabilities into your applications.

### 💡 Why Choose Our API?
- **Free for All:** Get started without any cost. Our API is open to everyone, making it an ideal playground for developers of all levels.

- **New Developer-Friendly:** If you're new to API development, don't worry! Our straightforward API endpoints and clear documentation will guide you through the process with ease.

- **Seamless Testing:** Experiment with web page screenshot capture without complex setup. Just provide the URL, choose your device, and decide if you want the full page or just the visible area.

- **Quick Integration:** Integrate screenshot capture into your applications, websites, or projects effortlessly. Our API's simplicity ensures a smooth development experience.

- **User-Loved:** Loved by developers for its simplicity and effectiveness, our API simplifies the often complex task of capturing web page snapshots.

### 🙏 Thanks to Our Developers
We'd like to extend a heartfelt thank you to all the developers who have contributed to the success of this API. Your dedication and feedback have been invaluable in making this service user-friendly and reliable. 🌟

### 📝 How to Get Started?
Getting started is a breeze:

 **😎 API Base URL:** `https://api.example.com`

1. **📷 Capture a Screenshot:-**
- **Endpoint:** `/`
- **Method:** GET
- **Description:** Capture a screenshot of a web page.
- **Query Parameters:**
  - `url` (string, required): The URL of the web page you want to capture.
  - `device` (string, required): The device to simulate (e.g., "desktop", "mobile").
  - `full` (string, required): Capture the full page ("on" for full, "off" for visible area).
- **Example Request:**
  ```
  GET /?url=https://example.com&device=desktop&full=on
  ```
- **Example Response:**
  ```json
  {
  "status": "success",
  "imgid": "pfa1nla28m673e8kcsslejckrl",
  "imgpat": "/img/?imgid=pfa1nla28m673e8kcsslejckrl"
  }
  ```
2. **🖼️ Get Screenshot Image:-**
- **Endpoint:** `/img`
- **Method:** GET
- **Description:** Retrieve the captured screenshot as an image.
- **Query Parameters:**
  - `imgid` (string, required): The image ID obtained from the previous request.
- **Example Request:**
  ```
  GET /img/?imgid=12345
  ```
- **Example Response:** (HTML with embedded image)
  ```html
  <html>
    <body style="padding: 0px; margin: 0px;">
      <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/4Q3zaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLwA8P3hwYWNrZXQgYmVnaW49Iu+7vyIgaWQ9Ilc1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCI/PiA8eDp4bXBtZXRhIHhtbG5zOng9ImFkb2JlOm5zOm1ldGEvIj48eDp4bXBtZXRhIHhtbG5zOnN0cmVhbWluZz0ieH..."/>
    </body>
  </html>
  ```

4. **Integrate & Enjoy:-** Incorporate the captured screenshots into your applications, websites, or projects. It's that simple!

### 📢 Important Notes
- Ensure all required query parameters are provided in your requests.
- Explore our user-friendly documentation for detailed usage instructions.

Begin your journey with the Screenshot API today, and experience the joy of effortless web page screenshot capture! 📸✨
### 🎉 Credits
We want to acknowledge and appreciate the hard work and creativity of our development team. They've made this API a reality. 🙌

- Lead Developer:  [**Dev. Gaurav Jatt 👨‍💻**](https://github.com/devgauravjatt)
- Backend Developer: [**Dev. Gaurav Jatt 👨‍💻**](https://github.com/devgauravjatt)
#