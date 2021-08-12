# ansibleTestProject

Hello! I added 2 roles in my playbook. This is docker and docker-compose.

Below is my project tree
.
├── ansible.cfg
├── hosts
├── playbook.yml
└── roles
    ├── docker
    │   ├── defaults
    │   │   └── main.yml
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   ├── main.yml
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    └── docker-compose
        ├── defaults
        │   └── main.yml
        ├── files
        │   └── docker-compose.yml
        ├── handlers
        │   └── main.yml
        ├── meta
        │   └── main.yml
        ├── README.md
        ├── tasks
        │   ├── main.yml
        │   └── main.yml.save
        ├── tests
        │   ├── inventory
        │   └── test.yml
        └── vars
            └── main.yml
