# html-curso Mi curso personal de mi persona de html 


version: '3.8' services: web: image: wordpress:latest ports: "8080:80" environment: WORDPRESS_DB_HOST: db WORDPRESS DB USER: exampleuser WORDPRESS_DB_PASSWORD: ${MYSQL_PASSWORD} WORDPRESS_DB_NAME: exampledb networks: frontend backend db
