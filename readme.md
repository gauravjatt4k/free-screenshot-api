
### 📑
Capture web page screenshots effortlessly with the Screenshot API. Simply provide the URL, choose a device simulation, and opt for full or visible area capture. Retrieve and integrate screenshots into your projects seamlessly. A user-friendly and efficient solution for web developers and applications. 📸✨

### 📝 How to Get Started?
Getting started is a breeze:

**😎 API Base URL:** `https://free-screenshot-api-code.vercel.app/`

1. **📷 Capture a Screenshot:-**
   - **Endpoint:** `/screenshot`
   - **Method:** GET
   - **Description:** Capture a screenshot of a web page.
   - **Query Parameters:**
     - `url` (string, required): The URL of the web page you want to capture.
     - `device` (string, required): The device to simulate (e.g., "desktop," "phone," "tablet").
     - `full` (string, required): Capture the full page ("on" for full, "off" for visible area).
   - **Example Request:**
     ```
     GET /?url=https://stackabuse.com/&device=desktop&full=on
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

3. **Integrate & Enjoy:-** Incorporate the captured screenshots into your applications, websites, or projects. It's that simple!

### 📢 Important Notes
- Ensure all required query parameters are provided in your requests.
- Explore our user-friendly documentation for detailed usage instructions.

Begin your journey with the Screenshot API today, and experience the joy of effortless web page screenshot capture! 📸✨

### 🎉 Credits
We want to acknowledge and appreciate the hard work and creativity of our development team. They've made this API a reality. 🙌

- Lead Developer: [**Dev. Gaurav Jatt 👨‍💻**](https://github.com/devgauravjatt)
- Backend Developer: [**Dev. Gaurav Jatt 👨‍💻**](https://github.com/devgauravjatt)
