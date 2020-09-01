all:
	project department office person role

project:
	java -jar jenkins-cli.jar -s http://15.185.210.44/jenkins/ -auth admin:token create-job project-assessment-site < project-assessment-site.xml

department:
	java -jar jenkins-cli.jar -s http://15.185.210.44/jenkins/ -auth admin:token create-job department-service < department-service.xml

office:
	java -jar jenkins-cli.jar -s http://15.185.210.44/jenkins/ -auth admin:token create-job office-service < office-service.xml

person:
	java -jar jenkins-cli.jar -s http://15.185.210.44/jenkins/ -auth admin:token create-job person-service < person-service.xml

role:
	java -jar jenkins-cli.jar -s http://15.185.210.44/jenkins/ -auth admin:token create-job role-service < role-service.xml



