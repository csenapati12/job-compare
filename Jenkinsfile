node(){
    stage("Compare"){
              def completeJobName = "$JOB_NAME"
              def actualJobName = "prod"
              if(completeJobName.contains("prod")){
                  print "Its a prod job"
                  echo "job name  ==="+actualJobName
                   print("/var/lib/jenkins/prodworkspace")
              }else{
                   print("Its QA job")
                   print("/var/lib/jenkins/qaworkspace")
              }               
                   
    }
}
