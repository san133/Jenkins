pipeline{
agent{
label 'node1'
}
stages{
stage('checkout')
{
steps
{
checkout scm
}
}
stage ('Creation of folder')
{
steps
{
sh "cd /home/ubuntu; sudo mkdir testfolder"
}
}

}
}
