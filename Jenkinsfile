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
                       println("completeJobName.substring(i, i+len)")
                       print("/var/lib/jenkins/projob")
               }else
               {
                   print("Its QA job")
                   print("/var/lib/jenkins/qajob")
               }
                   
                   
    }
}
 
