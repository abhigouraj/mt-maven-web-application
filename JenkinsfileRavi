node{

def mavenHome = tool name: "maven3.8.5"

//Checkout Stage 
stage('ChekoutCode'){
 git credentialsId: '34e0d9c1-4538-4a43-b898-74baa94aeee5', url: 'https://github.com/abhigouraj/mt-maven-web-application.git'
}

/*

//Build Stage
stage('Build'){
 sh "$mavenHome/bin/mvn clean package"
}

//Generate SonarQube Report
stage('SonarQubeReport'){
sh "$mavenHome/bin/mvn sonar:sonar"
}

//Upload Artifact into Artifactory repo
stage('UploadArtifactsIntoNexus'){
sh "$mavenHome/bin/mvn deploy"
}

//Deploy App into Tomcat Server
stage('DeployAppIntoTomcat'){
sshagent(['2f7131e0-752d-46ac-a0ff-279dc4de17dc']) {
sh "scp -o StrictHostKeyChecking=no  target/maven-web-application.war  ec2-user@3.91.9.174:/opt/apache-tomcat-9.0.89/webapps" 
}
}

*/
}//Node Closing
