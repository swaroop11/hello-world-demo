node {
    stage('Checkout') {
        // Replace with your repository URL
        git url: 'https://github.com/swaroop11/hello-world-demo.git', branch: 'main'
    }
    stage('Run Hello World Script') {
        // Make sure your script is executable or add 'chmod +x hello.sh'
        bat './hello-world.bat'
    }
}
