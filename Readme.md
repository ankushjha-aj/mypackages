# Push a image to github packages 
1. create image
2. create PAT  (personal access token) ON gITHUB
3. Authenticate GHCR
4. Tag and push our image to GHCR

echo "(YOur PAT TOKEN)" | docker login ghcr.io -u (your Username) --password-stdin

# use github actions to publih a Docker image to Github Packages (GHCR)
