// see https://dzone.com/refcardz/continuous-delivery-with-jenkins-workflow for tutorial
// see https://documentation.cloudbees.com/docs/cookbook/_pipeline_dsl_keywords.html for dsl reference
node {
   // Mark the code checkout 'stage'....
   stage 'checkout'
   sh 'echo run checkout code'

   //
   stage 'vendor'
   sh 'echo "echo run install all vendors"'

   //
   stage 'build'
   sh 'echo "run build code"'

   //
   stage 'deploy mutti'
   sh 'echo "deploy code to mutti"; sleep 5;'
}
