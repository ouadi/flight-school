# flight-school
learn to fly

# Start concourse

    sudo CONCOURSE_EXTERNAL_URL=http://172.17.0.3:8080 docker-compose up

# Start a concourse session

    fly -t ci login -c http://172.17.0.3:8080/

# Execute a task

    fly -t ci execute -c build.yml


