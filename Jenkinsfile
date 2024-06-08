node{

    stage('Clonar repositorio'){
        checkout scm
    }

    stage('Instalar dependencias'){
        bat 'npm install'
    }

    stage('Construir aplicacion'){
        bat 'npm run build'
    }

    /*stage('Copiar al servidor'){
        bat 'xcopy C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\Pipeline_Angular\\dist  C:\\servidor /E /I /Y'
    }*/
    

}