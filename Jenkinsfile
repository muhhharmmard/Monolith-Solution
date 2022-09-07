pipeline 
    agent any {
    stages {
        stage('Build') { 
            steps {
                docker-compose -f build docker-compose-build.yaml 
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