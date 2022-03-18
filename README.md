# wordcount-beam-go

## commands I have used for this project:
### check your GO version
        go version
### The go mod init command creates a go.mod file to track your code's dependencies.
        go mod init github.com/sowmya-yalamarthi/beam-go
### Get the SDK and the examples.
        go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
### I have installed wordcount.
        go install github.com/apache/beam/sdks/v2/go/examples/wordcount
### executing a wordcount.go with the sample input file.
        go run wordcount.go --input sample.txt --output sowmya
### If, I run the above command I got an error.
        go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
### Again execute wordcount.go then we will get the wordcounts.
          go run wordcount.go --input sample.txt --output sowmya
          
          
