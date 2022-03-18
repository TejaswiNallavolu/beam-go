# beam-go

1. Download Go from here. [Go download](https://go.dev/doc/install)
2. Install Go in your machine.
3. In project directory, create a folder named 'beam-go'
4. Open powershell with run as administrator and type this command

   `go mod init github.com/<yourgithubusername>/beam-go`
  
5. To check the version of go, use this command:

   `go mod init github.com/<yourgithubusername>/beam-go`
   
6. For getting Apache beam SDK,

   `go get -u github.com/apache/beam/sdks/v2/go/pkg/beam` 
   
7. To get wordcount program,
    
    `go install github.com/apache/beam/sdks/v2/go/examples/wordcount`
 
8. To run the wordcount program, type in the command 
    
    `wordcount --input <PATH_TO_INPUT_FILE> --output counts` 
    
    for example, I have used [input.txt](https://github.com/TejaswiNallavolu/beam-go/blob/main/input.txt) and my command should be:
    
    `wordcount --input input.txt --output counts`
    
 9. The output file will be generated with the name "counts".

## Run hello.go program

1. Created [hello.go](https://github.com/TejaswiNallavolu/beam-go/blob/main/hello.go)
2. Use the command `go run hello.go` from powershell to run hello.go


## Git commands you get before initializing the readme.md 

`echo "# beam-go" >> README.md`

`git init`

`git add README.md`

`git commit -m "first commit"`

`git branch -M main`

`git remote add origin https://github.com/TejaswiNallavolu/beam-go.git`

`git push -u origin main`
