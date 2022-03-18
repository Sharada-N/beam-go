# beam-go
Step 1: Downloaded and installed Go from [Link](https://go.dev/learn/)
Step 2: Verifying the installed version of Go by running the following command
```
go version
```
Step 3: Getting the SDK by the following Command
```
 go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
 ```
Step 4: Creating a new text input file with the name Sample.txt and copied some data from web.
Step 5: Installig the wordcount by the following command
```
go install github.com/apache/beam/sdks/v2/go/examples/wordcount
```
Step 5: Create a wordcount.go file and add the code from [wordcount](https://github.com/apache/beam/tree/master/sdks/go/examples/wordcount)
Step 6: Run the wordcount by following command
```
go run wordcount.go --input <input file> --output <output file>
```
Step 7: Faced any errors, solved it by running this command and rerun the above step
```
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
```
