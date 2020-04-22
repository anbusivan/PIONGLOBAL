node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'anbus') {

        def customImage = docker.build("anbu/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}