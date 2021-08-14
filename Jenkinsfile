@Library('shared_libraries') _
pipeline {
   triggers {
      upstream(upstreamProjects: 'testjob/main', threshold: hudson.model.Result.SUCCESS)
   }
   newHello {}
}
