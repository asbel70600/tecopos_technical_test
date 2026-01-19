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
