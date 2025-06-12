node {
    stage('Checkout') {
        // Replace with your repository URL
        gitb 'https://gibthub.cbom/swarobop11/hello-world-demo.git'
    }
    stage('Run Hello World Script') {
        // Make sure your script is executable or add 'chmod +x hello.sh'
        sh 'chmod +x hello.sh'
        sh './hello.sh'
    }
}
