# bam.iobio-docker
Container for https://github.com/chmille4/bam.iobio.io

### View your bam
```
docker run -it -p 4027:4027 quay.research.chop.edu/evansj/bamiobio bash

# now you are in the container
cd bam.iobio.io/
node www.js 

# go to localhost:4027/ in web browser
```
