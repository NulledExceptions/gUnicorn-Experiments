# gUnicorn-Experiments
testing playground for gunicorn--- https://www.digitalocean.com/community/tutorials/how-to-deploy-python-wsgi-apps-using-gunicorn-http-server-behind-nginx

brew install nginx

    Client Request ----> Nginx (Reverse-Proxy)

                              |
                        
                             /|\                 
                       
                            | | `-> App. Server I.   127.0.0.1:8081
                      
                            |  `--> App. Server II.  127.0.0.1:8082
                      
                             `----> App. Server III. 127.0.0.1:8083
                       



sudo -H pip install virtualenv


mkdir my_app

cd my_app

virtualenv my_app_venv

mkdir app


source my_app_venv/bin/activate


my_app              # Main Folder to Contain Everything Together

  |
  
  |=== my_app_venv  # V. Env. folder with the Python Int.
  
  |=== app          # Your application module
  
  |..
  
  |.
