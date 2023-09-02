# Two-tier-live-chat-in-cloud-application
<h2>Implementation</h2>
The project involved building a simple two-tier live chat application and deploying it on Google Cloud using both native and containerized setups. The flow of the project can be summarized as follows:<br><br>

MongoDB Installation:<br>
• Installed MongoDB, which served as the database server for storing chat messages.<br> • Followed the installation steps and validated the MongoDB installation on the database VM.<br><br>

Web Server Installation:<br>
• Implemented a web server using Python Flask, which acted as the communication layer between clients and the MongoDB server.<br> • Downloaded the source code for the web server and installed the required Python libraries.<br> • Configured the web server's IP address to connect it with the internal IP address of the MongoDB database VM.<br> • Started the web service and ensured its proper functioning.<br><br>

Live Chat Service Testing:<br>
• Accessed the live chat service through a web browser using the external IP address of the web server VM.<br> • Tested the live chat service across multiple sessions in different browsers to ensure that all users could see the same messages in real-time.<br><br>

4.Containerization:<br>

• Installed Docker on both the web server and database VMs.<br> • Downloaded the containerization source code for the project.<br><br>

MongoDB Containerization:<br>
• Completed the Dockerfile provided for MongoDB containerization.<br> • Built a container image for MongoDB using the Makefile.<br> • Ran the MongoDB container instance and verified its successful execution.<br> • Accessed the containerized MongoDB from the host machine to confirm the opened port.<br><br>

Web Server Containerization:<br>
• Completed the Dockerfile for containerizing the web server.<br> • Updated the Dockerfile to include the source code of the live chat web service.<br> • Modified the configuration file to connect the web server with the internal IP address of the MongoDB VM.<br> • Built a container image for the web server using Docker.<br> • Ran the web server container instance, ensuring the MongoDB container was running before starting the web server.<br><br>

Live Chat Service Validation:<br>
• Accessed and tested the live chat service again to confirm its functionality in the containerized setup.<br> • Ensured that the containerized live chat service could be accessed and used in the same way as the native setup.<br><br>

Project Completion:<br>
• Successfully deployed a containerized two-tier live chat application on Google Cloud.<br> • Leveraged cloud tools and technologies, such as Google Cloud Platform, Docker, and containerization, to enhance scalability and simplify deployment.<br> • Completed the project by demonstrating a working live chat application running in a cloud environment.<br><br>
