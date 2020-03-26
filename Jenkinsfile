node(){
    stage("Compare"){
              def completeJobName = "$JOB_NAME"
              def actualJobName = "prod"
              if(completeJobName.contains("Prod")){
                  print "Its a prod job"
                  echo "job name  ===   "+completeJobName
                   print("/var/lib/jenkins/prodworkspace")
              }else{
                   print("Its QA job")
                  echo "job name  === "+completeJobName
                   print("/var/lib/jenkins/qaworkspace")
              }               
                   
    }
}
