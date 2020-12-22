## Getting Started

    git clone https://github.com/Lotos2021/dev_ops_test_tasks.git

    cd dev_ops_test_tasks/task3

    docker-compose build
    docker-compose up


## Stop dev-loop

    docker-compose down

## Uninstall

    docker image ls -f dangling=true
    docker image rm $(docker image ls -f dangling=true -q)