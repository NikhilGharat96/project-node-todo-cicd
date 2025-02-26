# * Steps to execute node-todo-cicd project.

1. Create ec2 instance with ubuntu os<br>
2. Install jenkins and java: refer this link👇 for installation.<br>
   https://www.jenkins.io/doc/book/installing/linux/#debianubuntu

3. Add port no. 8080 in your Security Group to access jenkins.<br>
4. Then add jenkins user and passwd.<br>
   for jenkins password execute this on your server:<br>
   `sudo cat /var/lib/jenkins/secrets/initialAdminPassword`<br>
   copy passwd to access jenkins.<br>

5. In jenkins create freestyle job of any name eg. mynode<br>
   ![App Screenshot]()

