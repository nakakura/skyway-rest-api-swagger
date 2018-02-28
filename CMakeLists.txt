cmake_minimum_required(VERSION 3.9)
project(skyway_rest_api_swagger)

set(CMAKE_CXX_STANDARD 11)

add_executable(skyway_rest_api_swagger
        api/controllers/hello_world.js
        api/controllers/README.md
        api/helpers/README.md
        api/mocks/README.md
        api/swagger/swagger.yaml
        config/default.yaml
        config/README.md
        test/api/controllers/hello_world.js
        test/api/controllers/README.md
        test/api/helpers/README.md
        app.js
        manifest.yml
        package.json
        README.md)
