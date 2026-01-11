@Library('Jenkins-shared-library') _

def configMap = [
    project : "safety",
    component: "payment"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
      pythonEKSPipeline(configMap) // by default it will call, call function inside this pipeline
}
    echo "Please proceed with PROD process"
}