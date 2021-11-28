# Connecting Python and JavaScript with gRPC and Protocol Buffers

A code-along repo for the [youtube tutorial](https://youtu.be/-Mcvbz5J9kQ) by Evan Ugarte

## Libraries

### NPM

- @grpc/grpc-js
  - Pure JavaScript gRPC client.
- @grpc/proto-loader
  - A utility package for loading .proto files for use with gRPC, using the latest Protobuf.js package. Please refer to protobuf.js' [documentation](https://github.com/protobufjs/protobuf.js/blob/master/README.md) to understands its features and limitations.
- google-protobuf
  - The JavaScript runtime library for Google's data interchange format: Protocol Buffers.

### PIP

- google-pasta
  - pasta is an AST-based Python refactoring library
- grpcio
  - Package for gRPC Python.
- grpcio-tools
  - Package for gRPC Python tools.
- six
  - Six is a Python 2 and 3 compatibility library. It provides utility functions for smoothing over the differences between the Python versions with the goal of writing Python code that is compatible on both Python versions. See the documentation for more information on what is provided.
