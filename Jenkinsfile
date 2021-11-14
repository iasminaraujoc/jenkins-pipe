//configurando a pipeline

pipeline{
    agent any //qualquer agente

    stages{          //passos pelos quais a pipeline passa, 
                    //podemos ter quanto quisermos (build,test...)
        stage('Build'){

            steps{ //como o build é feito  

                sh 'echo "Oi para o nosso Jenkins"'
                sh '''
                    echo "Nossa primeira pipeline"
                    ls -la
                '''
            }
        }
    }


}