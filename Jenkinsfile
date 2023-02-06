pipeline{
    agent any
    stages{
	        stage ('DAST-->ZAP')
                {
			agent any
    			steps
                               {
         			bat 'java -jar C:\\Users\\Administrator\\Downloads\\OWASP\\ZedAttackProxy\\zap-2.10.0.jar -quickurl https://demo.testfire.net -quickout C:\\result_1.html -quickprogress -cmd'
    				}
		}
	}
}