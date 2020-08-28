# Instalação

### Exceute o comnado para criar os containers do Docker
- docker-compose up -d

### Acesse a pasta dos plugins
- cd wordpress/wp-content/plugins

### clone o plugin do Melhor Envio
- git clone git@bitbucket.org:melhor-envio/plugin-woocommerce.git

### Acesse a pasta do plugin do Melhor Envio
- cd plugin-woocomerce

### Instale as dependência do composer
- composer install

### Execute o Yarn para compilar os frontend do plugin
- yarn
