@Library([
    'continuous-deployment-library@improvement/allow-config-from-Jenkinsfile',
    'shared-library@improvement/allow-config-from-Jenkinsfile'
]) _

continuousDeployment(config: {
    app: {
    },
    strategy:  {
        type: ONE_BRANCH
    },
    build: {
        builder: none,
        container: nginx
    }
})
