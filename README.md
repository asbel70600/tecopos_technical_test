# Structure of the project:
This project is using git submodules, so it's into into
independent repos
The root project: **tecopos_technical_test** and:
tecopos_sso_service
tecopos_banking_service
tecopos_api_gateway
so to get the sources you need to do:
`git clone --recurse-submodules https://github.com/asbel70600/tecopos_technical_test`
`git clone --recurse-submodules git@github.com:asbel70600/tecopos_technical_test`

# How to deploy:
`docker compose up --build`

# Current Status:
The api-gateway offers a fiew routes but the only one working
is: http://127.0.0.1:3000/banking/accounts. It returns every account on mockapi.

The rest are developed but can't be used because of the sso service being
unable to run
