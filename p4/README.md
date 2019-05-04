##Práctica 4

Para esta práctica se ha realizado la configuración de la granja web incluyendo los servidores finales y el balanceador nginx. 

###Configuración SSL

Este certificado garantiza a los clientes que visitan nuestra página web que somos fiables y somos los que decimos ser, para ello utilizaremos el nuevo estandar TLS ya que SSL ya no se utiliza.

Para conseguir un certificado podemos hacerlo tramitándolo a través de una entidad certificadora, hacer un certificado propio o utilizando el proyecto Certbot. Nosotros utilizaremos la segunda opción mediante el uso de openssl.

Para realizar este certificado se han utilizado los siguientes comandos.
