node {

    checkout scm

    docker.withRegistry('192.168.0.136', 'pion') {

        def customImage = docker.build("anbu/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
