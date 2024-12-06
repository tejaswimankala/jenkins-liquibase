pipeline {
    agent any
    
    //   tools {
    // //     // Specify the Liquibase installation defined in Global Tool Configuration
    //       liquibase "liquibase"
    //      } 
      //environment {
    //LIQUIBASE_HOME = tool name: 'liquibase', type: 'org.jenkinsci.plugins.liquibase.install.LiquibaseInstallation'
      //}
    

    stages {
        stage('run ') {
            steps {
                script {
                    dir('C:/ProgramData/Jenkins/liquibase-4.23/liquibase/'){
                    //  def liquibaseCommand = tool 'liquibase'
                     
                      bat "liquibase --version"
                    }
                }
            }
        }
    }
}
