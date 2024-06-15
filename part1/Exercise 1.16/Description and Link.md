I deployed the course material (devopsdockeruh/coursepage:latest) on render.com.
Link: https://coursepage-latest.onrender.com

Detailed instructions:
1. Sign up at render.com
2. Go to https://dashboard.render.com/ and click "+ New" in the top right corner
3. Choose "Web Service"
4. Click on "Deploy an existing image from a registry"
5. In the Image URL tag, paste the image as <organisation>/<image>:<tag> (in this case devopsdockeruh/coursepage:latest)
(DockerHub is the assumed registry, so one has to make sure that the image is uploaded there.)
6. Click "Next"
7. Choose a name for the project (I left it as coursepage-latest in this case)
8. Choose the free tier under "Instance Type"
9. Click "Create Web Service"

Voila!
