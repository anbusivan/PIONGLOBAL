node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Abirami@002-anbus') {

        def customImage = docker.build("anbu/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
