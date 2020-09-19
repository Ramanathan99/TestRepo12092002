def test1 = "a"
def test2 = "b"
def test3 = "c"

node(){

  stage ('cloning repo')
    {
      checkout scm
}
  
  
stage("shell commands"){
sh "ls -la"
}
  
  stage("print value of test1 ")
{
  echo "value of test is ${test1}"
}

stage("print value of test2")
{
  echo "value of test is ${test2}"
}


stage("print value of test3")
{
  echo "value of test is ${test3}"
}

}
