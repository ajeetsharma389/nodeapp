node
{
	checkout scm
	def myEnv = docker.build 'ajeetsharma389/nodeapp:100'
	myEnv.run('docker run -p 49160:8080 -d ajeetsharma389/nodeapp:100')
	
}