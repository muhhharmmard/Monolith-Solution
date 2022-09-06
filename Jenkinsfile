pipeline 
    agent any {
        environment{
        
        registry = "doctorcodes/udagram-api-feed"
        registryCredential = 'dockerhub'        
        
     }
    stages {
        stage('Build') { 
            steps {
               sh 'docker-compose -f docker-compose-build.yaml build --parallel'
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy Image') {
            steps{
          //    script {
            //    docker.withRegistry( '', registryCredential ) {
              //  dockerImage.push()
            //}
        }
    }
}
    }
   






















// pipeline{
//     agent any
//     }
//     environment{
        
//         registry = "doctorcodes/udagram-api-feed"
//         registryCredential = 'dockerhub'        
//     }
    
//     stages{
//        stage('Building image') {
//       steps{
//         script {
//           dockerImage = docker.build registry 
//         }
//       }
//     }
//        stage('Deploy Image') {
//       steps{
//          script {
//             docker.withRegistry( '', registryCredential ) {
//             dockerImage.push()
//           }
//         }
//       }
//     }
// }