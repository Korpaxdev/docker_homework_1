# For create a docker image use a command:

### `docker build <path_to_dockerfile> -t <name_of_container>`

## Example:

`docker build . -t my_nginx_image`

# For run a container use a command:

### `docker run -d -p <your port>:80 -v <your_path_to_html_folder>:/usr/share/nginx/html --name <your_name_of_container> <name_of_nginx_image>`

## Example:

`docker run -d -p 80:80 -v ./html:/usr/share/nginx/html --name my_nginx_container my_nginx_image`
