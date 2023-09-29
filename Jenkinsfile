@Library([
    'continuous-deployment-library@improvement/allow-config-from-Jenkinsfile',
    'shared-library@improvement/allow-config-from-Jenkinsfile'
]) _

continuousDeployment(
	configGitBranch: 'master',
	config: [
		parent: "duvalhub/parent.yml",
		app: [
			group: "huguesmcneilduval"
		],
 		strategy:  [
			type: "ONE_BRANCH"
		],
		build: [
			builder: "none",
 	  	container: "nginx"
		],
		deploy: [
			platforms: [
				prod: [
					hostnames: [
						"huguesmcneilduval.duvalhub.com"
					]
				]
			]
		]
	]
)
