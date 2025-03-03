### SAKARYA UNIVERSITY - SOFTWARE ENGINEERING DEPARTMENT
# SWE 304 SOFTWARE DEVELOPMENT PROCESSES (DEVOPS)


## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Publishing a web app on a cloud.</b></td>
      <td> 
        <b>a)</b> Show that you can build a Java app in jar format on your local computer using Maven. <br> 
        <b>b)</b> Upload that jar file using SFTP to Azure or AWS cloud (on Virtual Machine or EC2 instance). <br> 
        <b>c)</b> Set up web server (Nginx, and DB server (MySQL) on the cloud. <br> 
        <b>d)</b> Show that local client (browser on your computer) can access the app GUIs and the app runs on Azure or AWS as expected. 
      </td>
      <td>6 March 2025</td>
      <td><a href="pro1.pdf">Project1</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>Virtualization with Docker-Compose.</b></td>
      <td>
        <b>a)</b> Build the app. in jar on your local computer using Gradle.<br> 
        <b>b)</b> Put your app. into Docker container and push it to Docker Hub. (Do not push the DB server image)<br> 
        <b>c)</b> Create EC2 instance on AWS or VM on Azure.<br>
        <b>d)</b> Pull the uploded app. image and available latest PostgreSQL image from Docker Hub.<br>
        <b>e)</b> Integrate S3 (or blob) storage to your application.<br>
        <b>f)</b> Run your app. with all components. <br>
        <b>g)</b> Start Nginx web server and show that your app. is accessible from given public IP and port 80.
      </td>
      <td>27 March 2025<br></td>
      <td><a href="pro2.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Jenkins declarative pipeline for publishing an application.</b></td>
      <td>
        <b>a)</b> Build the web app in jar on your local computer using Gradle.<br>
        <b>b)</b> Create a declerative pipeline on Jenkins server that do the following tasks: <br>
          - Build the jar file on GitHub. <br>
          - Build a containerized image on GitHub. <br>
          - Push the image file to the DockerHub <br>
        <b>c)</b> Pull the images (webapp and DB) from DockerHub to AWS (or Azure) cloud. <br>
        <b>d)</b> Run your application on cloud instances.<br>
        <b>e)</b> Show that your application runs as expected.<br>
      </td>
      <td>8 May 2025<br></td>
      <td><a href="pro3.pdf">Project3</a></td>
    </tr>
     <tr>
      <td>4</td>
      <td><b>Publishing on Kubernetes cluster.</b></td>
      <td>
        <b>a)</b> Build the web app in jar on your local computer using Gradle.<br>
        <b>b)</b> To be announced. <br>      
        <b>c)</b> To be announced. <br>
        <b>d)</b> Run your application on Kubernetes cluster.<br>
        <b>e)</b> Show that your application runs as expected.<br>
      </td>
      <td>22 May 2025<br></td>
      <td><a href="pro4.pdf">Project4</a></td>
    </tr>
  </body>
</table>


## General rules for project grading:
* Groups are allowed 10 minutes to present their work.
* Groups are called to present their work based on a random number announced in the class. 
* One person can be a speaker or members can present stages separately in one session.
* All group members are expected on the board while presenting. Absent members will be penalized according to excuse.
* Group members help each other to hook their computer to the projector quickly.
* Members (and groups) who are not contributed at all, and do not show up at presentation will get 0 (zero) grade.


1. Cloud publishing: Running jar file on AWS Cloud
2. Virtualization: Publishing application on AWS using Docker-Compose
3. Continuous deployment: Deploy pipeline using Jenkins
