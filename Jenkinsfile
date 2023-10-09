pipeline{

agent { node { label 'Agent-1'} }

stages{

    stage ('build') {

    steps{
        echo ' the BUILD for git-hub web-hook triggers'
    }
    }
    stage ('test'){

    steps{
        echo 'This is test stage'
    }
    }
    stage ('deploy'){

    steps{
        echo 'This is deploy stage'
    }  
    }
}
}