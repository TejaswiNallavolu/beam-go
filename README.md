# beam-go

- Download Go from here. [Go download](https://go.dev/doc/install)
- Install Go in your machine.
- In project directory, create a folder named 'beam-go'
- Open powershell with run as administrator and type this command

  `go mod init github.com/<yourgithubusername>/beam-go`
  
- To check the version of go, use this command:

   `go mod init github.com/<yourgithubusername>/beam-go`
   
 - For getting Apache beam SDK,

   `go get -u github.com/apache/beam/sdks/v2/go/pkg/beam` 
   
 - To get wordcount program,
    
    `go install github.com/apache/beam/sdks/v2/go/examples/wordcount`
 
 - To run the wordcount program, type in the command 
    
    `wordcount --input <PATH_TO_INPUT_FILE> --output counts` 
    
    for example, I have used input.txt and my command should be:
    
    `wordcount --input input.txt --output counts`
    
  - The output file will be generated with the name "counts".
