node {
   checkout scm
   sh 'npm install'
   final b = nxInitializeBuild(projectName: 'test', base: "origin/master~1", head: "origin/master")
   nxLintAffected b
   nxBuildAffected b
}
