node {
 
  
    stage('Build') {
    
        appscan application: '979132c6-0c91-4edd-9f76-d46bd845d076',
          credentials: 'hcldast',
          email: true,
          failBuild: false,
          failBuildNonCompliance: false,
          failureConditions: [],
          name: BUILD_NUMBER,
          scanner: dynamic_analyzer(hasOptions: true, loginPassword: "${params.TestFire_Pass}", loginUser: '${params.UserName}',
            optimization: 'Fast', scanType: 'Staging',
            target: 'https://demo.testfire.net?mode=demo'),
          target:'', type: 'Dynamic Analyzer', wait: false
      
    
  }
}