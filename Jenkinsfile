node {
    stage('Checkout') {
        // Replace with your repository URL
        git url: 'https://github.com/swaroop11/hello-world-demo.git', branch: 'main'
    }
    stage('List Files') {
        sh 'ls -l'
    }
    stage('Run Hello World Script') {
        // Make sure your script is executable or add 'chmod +x hello.sh'
        sh 'chmod +x hello-world.sh'
        sh './hello-world.sh'
    }
}
