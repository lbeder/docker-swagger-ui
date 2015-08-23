# Swagger UI for Docker

This Dockerfile packages up Swagger UI and runs it with Nginx.

## Setting the Swagger URL

You can set the Swagger URL at runtime by setting the URL environment variable.

## Example

`docker run -it --rm -p 3000:80 --name test -e "URL=http://petstore.swagger.io/v2/swagger.json" lbeder/swagger-ui`

Check your stack after deploying to get your URL to test with.
