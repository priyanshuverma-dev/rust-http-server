This repository contains a README file sample for Daytona Samples and the MIT License.

It can be used as a template to create sample repositories that can be added into [Daytona](https://github.com/daytonaio/daytona).

Once you finish your sample and it gets merged, you can open a PR in the Daytona repo and submit the sample into the [index file](https://github.com/daytonaio/daytona/blob/main/hack/samples/index.json).

# Rust Http Server

This project is a build of a web server in Rust on bare minimum from scratch with only `std::TCPListener`. This is only a fun project to learn rust.

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create <SAMPLE_REPO_URL> 
   ```  

3. **Build Application**:  
   ```bash  
   cargo build
   ``` 

4. **Start the Application**:  
   ```bash  
   cargo run
   ```  
   Running on `http://localhost:5000`

---

## ✨ Features  

1. It supports api requests and html files,
2. We can create a api route for the following methods:
  * GET
  * POST
  * PUT
  * DELETE

  *We can add more but as of now I don't have time to add them, If you want then feel free to add and work around.*

3. The Project is completely memory safe as the language Rust is and very performance effective as it doesn't and a clone of any request and saves every bit of memory.