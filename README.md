# Access-Webpage-using-HTTPD-in-Linux
In this project I have used HTTPD web server to host web pages in Linux, how we can set up a web server in our Linux environment, deploy our first simple HTML-based web page, and how we can access our web page from the browser.

 **What is HTTPD ?**

HTTP Daemon is a software program that runs in the background of a web server and waits for incoming server requests.

The daemon answers the request automatically and serves the hypertext and multimedia documents over the Internet using HTTP.

1. **Launch an EC2 Instance:**
- You initiate a new EC2 instance on AWS, selecting the AWS Linux image
- Connect to EC2 Instance through EC2 Instance Connect
2. **Install HTTPD Web Server:**
- Install the HTTPD web server using the yum package manager with all dependencies
- 3. **Check HTTPD server stuatus:**
- Check HTTPD server active or not using systemctl utility

4. **Start HTTPD server in server:**

5. **Create web page:**
- Go to the directory where the webpage content file is located (`/var/www/html`).
- Create a new `index.html` file with your own content.
- If you add Images to your content add images in html directory

6. **View Customized Page:**
- Use the public IP address again in the browser to see your website content.
