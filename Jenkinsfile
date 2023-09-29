continuousDeployment(
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
