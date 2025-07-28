Basics of Web Development : Focus on communication between computers over the internet.



🧠 Core Concept: The internet relies on IP addresses and DNS (Domain Name System) to locate websites.



🖥️ Step-by-step Breakdown:

1. User enters a website name (e.g., chaicode.com) in the browser.
2. The request goes to the ISP (Internet Service Provider).
3. The ISP checks with the DNS server (like a phonebook) to find the IP address for the website:
4. DNS translates chaicode.com to an IP address like 192.168.2.5.
5. The IP address is returned to the ISP (e.g., 76.76.21.21), and then sent back to the user's computer.
6. With the IP address, your computer sends a request to the actual server of the website through the internet (represented by the globe icon).
7. The server responds and loads the website on your browser.





* 📓 Extra Notes:

DNS = phonebook of the internet — It maps domain names to IP addresses.



Domain name providers (e.g., Namecheap, GoDaddy, BuyNow) allow you to register domain names like chaicode.com.



Google, AWS, Azure, Digital Ocean host our website and keep their systems running the whole time for our websites to be available the whole time.





----

Big Picture of Web Application : 



🌐 1. User/Website Makes a Request to Server

This happens when:



* You visit a URL
* Click a button
* Submit a form
* Or do anything that needs new data



👉 The browser sends a request to a server.



🖥️ 2. Server Responds

Once the request reaches the server, it performs two main tasks:

* Searches the database (if needed): For example, if you request your profile, it looks up your details in the database.
* Responds: It sends back the required data.



📦 3. What Does the Server Send?

The server usually sends three types of files to the browser:



HTML (Structure)

The content and layout of the page.

Ex: Headings, paragraphs, images, forms, etc.



CSS (Style)

Controls the look and feel of the page.

Ex: Colors, fonts, spacing, layout, animations.



JavaScript (Functionality)

Adds interactivity and logic.

Ex: Handling clicks, validating forms, loading more content without refreshing.

📌 JavaScript can also send or receive data from the server (like when using fetch() or XMLHttpRequest).



---------

Frontend, Backend and API

🔁 1. Frontend ↔ API ↔ Backend ↔ Database



✅ Frontend (What the user sees)

* Built with HTML, CSS, JavaScript\\
* Often enhanced with frameworks like React
* Uses libraries like:
* &nbsp;   Tailwind CSS (utility-first CSS framework)
* &nbsp;   Bootstrap (pre-styled components)



🔌 API (Application Programming Interface)

* Acts like a bridge between frontend and backend
* Frontend sends a request to the API
* Backend responds via the API and Response is usually in JSON format



⚙️ Backend (The logic and data-handling part)

Code that runs on a server

Written in programming languages like:

* Node.js
* PHP

Server receives request → processes it → responds



🗃️ Database (Stores data)

The backend interacts with a database to:

* Save
* Retrieve
* Update
* Delete data

Examples:

* MongoDB (NoSQL)
* MySQL
* PostgreSQL



🍽️ Analogy: Web App is like a Restaurant

* Frontend = Tables where you are served
* API = The waiter
* Backend = Kitchen (prepares food, handles logic)
* Json = Plates on which you are served





