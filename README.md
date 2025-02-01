# INTEGRATE-SECURITY-SCANNING-TOOLS-LIKE-SONARQUBE-OR-OWASP-ZAP-INTO-A-PIPELINE

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: DEEPAK PRASAD

**INTERN ID**: CT6WGAP

**DOMAIN**: DEVOPS

**BATCH DURATION**: DECEMBER 25th, 2024 to FEBRUARY 10th, 2025

**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

Integrate security scanning tools like sonarqube owasp zap in to a pipeline view
first i have to create ec2 instance and select ubuntu amazon machine image and select t2 micro after this 
i will select key pairs, storage 20 gb magnetic storatge and security group select ssh, http, custom tcp with port 8080 so that
it will open page jenkins because jenkins page will open only this port.
at last launch the ec2 machine
now connect this ec2 instance to instance connect so that it will keep connect now 
first step is to get root user and update our machine sudo apt-get update
and then i have to install java version 17 so sudo apt install openjdk-17-jre
after this i will paste all code for jenkins installation it will take time for install then i will put public ip address to 
the google page so that it will work like http://3.87.32.46:8080 and after this jenkin page will appear and i have to take jenkins
code and put this to our linux page so it will work and get password so i will do cat and that code so it will work and get password
and that password i will put on that jenkins page and jenkins have ask some credentials so that it will ask name password and many more
like email user name so i have to put all things. then it will show jenkins page and here we configure all set up for sonar qube and owasp
now i will go to managed jenkins and go to plugins and i have to put owasp dependency check then i have to install it and now search opejdk and select eluminated option and install
it now get back from plugins and go to tools option and configure add jdk and tick the option install automatically and add maven option and put name maven and install automatically
now go down and click on add dependency check option and name write DP-check and install automatically now i have to add sonar qube so click on add sonar qube scanner option 
write the name and click to apply and save all.
now i have to create job so go to new item and put name and select freestyle project 
page will open here and description you can write and tick on discards old builds now in source code git code i have to paste and now configuration part is over now build 
the project it will run and you can see console output and if any issues is there you can fix it otherwise it will shows error.
here now i will create another job name owasp sonar and select it pipeline if it is showing here. now in description we write something and here select discard old builds. here it is same as freestyle only difference is we have to write script in this 
pipeline script so it will work and give result in html format. so it will show the job here and shows all dependency and sonar qube scanning page will appear.now you can check.
