node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("raj22abhishek/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}