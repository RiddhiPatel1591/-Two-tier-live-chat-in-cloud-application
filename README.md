# Two-tier-live-chat-in-cloud-application
<h2>Implementation</h2>
The project involved building a simple two-tier live chat application and deploying it on Google Cloud using both native and containerized setups. The flow of the project can be summarized as follows:

MongoDB Installation:
• Installed MongoDB, which served as the database server for storing chat messages. • Followed the installation steps and validated the MongoDB installation on the database VM.

Web Server Installation:
• Implemented a web server using Python Flask, which acted as the communication layer between clients and the MongoDB server. • Downloaded the source code for the web server and installed the required Python libraries. • Configured the web server's IP address to connect it with the internal IP address of the MongoDB database VM. • Started the web service and ensured its proper functioning.

Live Chat Service Testing:
• Accessed the live chat service through a web browser using the external IP address of the web server VM. • Tested the live chat service across multiple sessions in different browsers to ensure that all users could see the same messages in real-time.

4.Containerization:

• Installed Docker on both the web server and database VMs. • Downloaded the containerization source code for the project.

MongoDB Containerization:
• Completed the Dockerfile provided for MongoDB containerization. • Built a container image for MongoDB using the Makefile. • Ran the MongoDB container instance and verified its successful execution. • Accessed the containerized MongoDB from the host machine to confirm the opened port.

Web Server Containerization:
• Completed the Dockerfile for containerizing the web server. • Updated the Dockerfile to include the source code of the live chat web service. • Modified the configuration file to connect the web server with the internal IP address of the MongoDB VM. • Built a container image for the web server using Docker. • Ran the web server container instance, ensuring the MongoDB container was running before starting the web server.

Live Chat Service Validation:
• Accessed and tested the live chat service again to confirm its functionality in the containerized setup. • Ensured that the containerized live chat service could be accessed and used in the same way as the native setup.

Project Completion:
• Successfully deployed a containerized two-tier live chat application on Google Cloud. • Leveraged cloud tools and technologies, such as Google Cloud Platform, Docker, and containerization, to enhance scalability and simplify deployment. • Completed the project by demonstrating a working live chat application running in a cloud environment.
