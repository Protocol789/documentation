
# Summary

   URL: **paperless.zorab.im**  
   Int: backend.server:8008 
   Credentials: Local U/P  

## Installation  

1. Installed using quick code below which created docker-compose file for you via prompts  
   `bash -c "$(curl -L https://raw.githubusercontent.com/paperless-ngx/paperless-ngx/main/install-paperless-ngx.sh)"` 

## Config  

* Local proxy via: 
  * Nginix Proxy Manager
  * Pi Hole DNS (zorab.im)
* Cloudflare application via Zero trust

### Unique

* Uses several methods to ingest the documents in. Setup the following
  * Desktop via browser
  *    Installed samba and shared directory for drop in the 'consume' blackhole dir
  * Mobile `no paper app` to directly upload via API
  * Email integration
    * Using secondary gmail account via IMAP and app password to connect

### Directory  

   docker compose   : `/home/docker/daniel/paperless-ngx`  
   data files       : `/home/docker/daniel/paperless-ngx`

### 

#### Links  

   [Paperless Github Repo](https://github.com/paperless-ngx/paperless-ngx)
