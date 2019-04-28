# Go-Tutorial
Setup Go Programming Environment


# Installation steps for GoLang [Linux]

## Step-1 Download the specific tar from this download https://golang.org/dl/
   - Example: 
   ```sh 
   $ wget https://dl.google.com/go/go1.11.linux-amd64.tar.gz
   ```
   
## Step-2 Untar the golang binary into /usr/local directory
   - Example: 
   ```sh 
   $ tar -xzvf go1.11.linux-amd64.tar.gz 
   $ mv go /usr/local/
   ``` 
   
## Step-3 Setup the environment variables [GOROOT,GOPATH,PATH] for golang
   - GOROOT [It is the variable that will keep where the go binary is installed]
   - GOPATH [It is the variable that will keep where the go-project is going to create]
   - PATH [Linux path variable]
   ### Example:
   ```sh 
   $ GOROOT=/usr/local/go
   $ export GOPATH=$HOME/Projects/BrCampaign
   $ export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
   ``` 
   - you can update this to end of .profile file, after updating source the profile:
   ```sh
   $ source ~/.profile
   ```
