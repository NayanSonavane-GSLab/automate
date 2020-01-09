pipeline{
    agent any
    stages{
        stage('Enviroment'){
            steps{
                    echo "Selected environment:-> ${ENV}";
                }
            }
            stage('Application'){
                steps{
                    echo "Selected Application:-> ${APP}";
                }
            }
            stage('ImageTAG'){
                steps{
                    echo "Selected IMAGE_TAG:-> ${IMAGE_TAG}";
                }
            }
            
            stage('Deploy'){
                steps{
                    echo "Pass!!";
                }
            }
        }
     }
