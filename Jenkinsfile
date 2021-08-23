// pipeline {
//     agent any

//     stages {
//         stage ('Compile Stage') {

//             steps {
//                 withMaven(maven : 'maven_3_5_0') {
//                     sh 'mvn clean compile'
//                 }
//             }

//         }
//     }
// }
pipeline {
    agent {
        docker { image 'amazoncorretto:11' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java --version'
            }
        }
    }
}
