pipeline {
    agent any
environment {
     PATH = "/opt/maven/bin:$PATH"
	 }

    stages {
        stage("build"){
            steps {
                 echo "----------- build started ----------"
                 sh 'mvn clean deploy'
                 echo "----------- build compeleted --------"
    }
}
    }
}
