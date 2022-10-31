node {
    stage('cloning git repo') {
        git branch: 'main', url:'https://github.com/naiveskill/devops.git'
        sh "chmod +x -R ./jenkins"
        sh "./jenkins/script/scripted_pipeline_ex_2.sh"
    }
}
