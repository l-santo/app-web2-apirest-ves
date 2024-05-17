node{

    stage('Clonar repositorio'){
        checkout scm
    }

    stage('Instalar dependencias'){
        bat 'npm install'
    }

    stage('Construir aplicación'){
        bat 'npm run build'
    }

  /*  stage('Copiar al servidor'){
        bat 'xcopy '
    }
    */

}