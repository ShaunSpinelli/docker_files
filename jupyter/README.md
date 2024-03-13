
build

`docker build . -t jupyt`

start and map through current directory
 
`docker run -p 8888:8888 -v $(pwd):/work jupyt`