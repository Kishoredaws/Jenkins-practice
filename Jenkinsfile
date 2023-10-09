pipeline{

agent { node { label 'Agent-1'} }

stages{

    stage ('build') {

    steps{
        echo ' build'
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