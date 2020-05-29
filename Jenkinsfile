pipeline {
   agent any

   stages {
      stage('Run Script') {
         steps {
            echo 'Running Script'
            sh '''
              python scripts/my_script.py
            '''
         }
      }
   }
}
