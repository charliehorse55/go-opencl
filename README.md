# OpenCL bindings for Go

Documentation at <http://godoc.org/github.com/jgillich/go-opencl/cl>.

See the [test](cl/cl_test.go) for usage examples.

By default, the OpenCL 1.2 API is exported. To get OpenCL 1.0, set the build tag `cl10`.


Differences from the jgillich:
-----------------------------------
Fixed cl.Flush() calling clFinish(), and added additional APIs for asynchronous use

