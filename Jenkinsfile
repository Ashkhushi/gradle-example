node {
 stage 'Clone sources'
  git url: 'https://github.com/Ashkhushi/gradle-example'
  
 stage('Gradle Build') {
    if (isUnix()) {
        sh './gradlew clean build'
    } else {
        bat 'gradlew.bat clean build'
    }
}

}
