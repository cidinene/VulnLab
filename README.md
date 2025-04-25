
  <h3 align="center">VulnLab</h3> 

  <p align="center">
    A web vulnerability lab project developed by Yavuzlar.
    ## Contact

    [Website](https://siberyavuzlar.com/) </br>  
    [Linkedln](https://www.linkedin.com/company/siberyavuzlar) <br>
    [Twitter](https://twitter.com/siberyavuzlar) </br>
    [Instagram](https://www.instagram.com/siberyavuzlar/)
  </p>
   
</p>

<a href="https://s10.gifyu.com/images/Animation387bbf064343cb3fe.gif">
    <img src="https://s10.gifyu.com/images/Animation387bbf064343cb3fe.gif" alt="Logo"  >
</a>

<!-- Vulnerabilities List -->
## Vulnerabilities

* SQL Injection
* Cross Site Scripting (XSS)
* Command Injection
* Insecure Direct Object References (IDOR)
* Cross Site Request Forgery (CSRF)
* XML External Entity (XXE)
* Insecure Deserialization
* File Upload
* File Inclusion
* Broken Authentication
* Race Condition
* Server Side Template Injection (SSTI)
* API Hacking
* Captcha Bypass
* Path Traversal

<!-- Installation -->
## Installation

### Install with DockerHub

1. If you want to install on DockerHub, just type this command.
   ```sh
    docker run --name vulnlab -d -p 1337:80  docker run --name vulnlab -d -p 1337:80 ghcr.io/cidinene/vulnlab/webapp:latest
   ```
2. Go to http://localhost:1337

### Manual Installation

1. Clone the repo
   ```sh
    git clone https://github.com/cidinene/VulnLab
   ```
2. Build docker image
   ```sh
    docker build -t cidinene/vulnlab .
   ```
3. Run container
   ```sh
    docker run -d -p 1337:80 cidinene/vulnlab
   ```
4. Go to http://localhost:1337

### Google Cloud

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/cidinene/VulnLab)

<!-- SPONSOR -->



