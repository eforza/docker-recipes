docker run -it \
  -v $PWD/config:/drouter/config \
  -v $PWD/local:/drouter/local \
  -e DATAPOWER_ACCEPT_LICENSE=true \
  -e DATAPOWER_INTERACTIVE=true \
  -p 9090:9090 \
  -p 9022:22 \
  -p 5554:5554 \
  -p 8000-8010:8000-8010 \
  --name idg \
  ibmcom/datapower:7.5.2.0.281259


https://developer.ibm.com/datapower/config/

https://raw.githubusercontent.com/ibm-datapower/datapower-tutorials/master/getting-started/import/hello-world.zip


docker run -it   -v $PWD/config:/drouter/config   -v $PWD/local:/drouter/local   -e DATAPOWER_ACCEPT_LICENSE=true   -e DATAPOWER_INTERACTIVE=true   -p 9090:9090   -p 9022:22   -p 5554:5554   -p 8000-8010:8000-8010   --name idg   ibmcom/datapower:7.5.2.0.281259
