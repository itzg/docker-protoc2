This Google Protobuf compiler image is for projects that need an "ancient"
version of the `protoc` compiler.

## Usage

    docker run -it --rm -v $PWD:/src itzg/protoc2:2.4.1 [OPTION] PROTO_FILES

where `OPTION` and `PROTO_FILES` are standard command-line parameters of protoc itself.
Use `--help` to see the available options.
