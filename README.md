# Deploy an ASP.NET Core App on Section Tutorial
This repo holds the sample code for usage with the tutorials hosted on Section.io's documentations.

Refer to [Tutorials/Aspnetcore](https://www.section.io/docs/tutorials/frameworks/aspnetcore/) for detailed instructions on deploying to Section.

# Build and push aspnetcore image
```
USER=section
IMAGENAME=my-aspnetcore-app
TAG=0.0.1

docker build . --tag ghcr.io/$USER/$IMAGENAME:$TAG
docker push ghcr.io/$USER/$IMAGENAME:$TAG
```
