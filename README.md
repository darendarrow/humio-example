# Example run

Clone this repo to ~/src/humio or update the file paths in the example

```bash
docker run -v $HOME/src/humio-example/humio-data:/data -v $HOME/src/humio-example/humio-ro:/etc/humio:ro --net=host --name=humio --ulimit="nofile=8192:8192" --env-file=$HOME/src/humio-example/humio.conf  humio/humio
```

Humio is now running. Navigate to http://localhost:8080 to view the Humio web interface.

Press Ctrl-C to exit when done.
