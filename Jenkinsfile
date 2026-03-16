 node {
 try {

 stage('Build') {
 sh '''
 echo "Building project..."
 ls
 echo "Build successful"
 '''
 }

 stage('Test') {
 sh '''
 echo "Running tests..."
 echo "Tests completed"
 '''
 }

 stage('Deploy') {
 sh '''
 echo "Deploying application..."
 echo "Deployment successful"
 '''
 }

 echo "Pipeline executed successfully!"

 } catch (Exception e) {

 echo "Pipeline failed!"
 throw e

 }
}
