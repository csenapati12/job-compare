 node(){
    stage("Compare"){
              def completeJobName = "$JOB_NAME"
               def actualJobName = "prod"
               int len = actualJobName.length();
               boolean occurance = false
               int i = 0;
               while (!completeJobName.regionMatches(i, actualJobName, 0, len)) {
                       i++;
                       occurance = true;
               }
               if (occurance) {
                      print "Its a prod job"
                       print("/var/lib/jenkins/prodworkspace")
               }else
               {
                   print("Its QA job")
                   print("/var/lib/jenkins/qaworkspace")
               }
                   
                   
    }
}
 
