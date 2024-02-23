pipeline
{
agent any
stages
{
stage("GIT")
{
steps
{
git "https://github.com/Challavenkateswarlu/jenkins.git"
}
}
stage("Run")
{
steps
{
sh Jenkinsfile
}
}
}
}
