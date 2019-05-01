# REST-api-testing
Testing REST endpoints of a sample service


Build and run the application locally with docker
---------------------------------

    build           docker build -t rest-sample .
    Run             docker run --name rest-sample-container -e SPRING_PROFILES_ACTIVE=local -p 8080:8080 rest-sample
    
    application will be available on http://localhost:8080/swagger-ui.html#/
