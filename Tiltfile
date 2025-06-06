docker_build('simpleportfolio-image', '.', dockerfile='dev.Dockerfile')
k8s_yaml('dev-deployment.yaml')
k8s_resource('simpleportfolio', port_forwards=4321)
