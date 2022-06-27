# usdzconvert-docker
Apple usdzconvert 0.66 in a docker image

## Usage

### Powershell / Linux 

`docker run -v ${PWD}:/mnt/assets --rm michaelgold/usdzconvert /mnt/assets/your-gltf-file.glb`

## Notes

- You can run this in any directory that contains glb files. Just reference the file by its location in the docker container, for example: `/mnt/assets/your-gltf-file.glb`
- If you build this Dockerfile from source, make sure to use at least 6GB ram for your Docker container
