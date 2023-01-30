                            ------------------------------------------------------
                                            Docker Volumes
                            ------------------------------------------------------                
1. Load docker | docker version 20.10.22 |
2. Clone this --> | git clone https://github.com/Sur1010/Docker_Volume.git |
3. Build the image --> | docker build -t "name" . |
4. Run container whit | docker run -dt -p 80:80 --name "name" -v MyVolume:/var/www/html "image name" |
                                           | Or |
5. Run container whit | docker run -dt -p 80:80 --name "name" -v /your File Path:/var/www/html "image name" |                                         
                   
