pipeline {
    agent any
environment {
     PATH = "/opt/maven/bin:$PATH"
	 }

    stages {
        stage("build"){
            steps {
                 echo "----------- build started ----------"
                 sh 'mvn clean install'
                 echo "----------- build compeleted --------"
    }
}
    }
}
