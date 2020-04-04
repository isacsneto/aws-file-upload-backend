# aws-img-upload
Código desenvolvido para integrar o spring ao aws s3 para guardar arquivos em buckets.

Para que aplicação funcione corretamente é necessário que o usuário tenha uma conta na Amazon Web Services(BR) e
deposite suas credenciais(accessKey e secretKey) no arquivo src/main/resources/application.properties.
Após isso você pode rodar a api com os seguintes comandos:
1. mvn clean install
2. java -jar target/upload-image-aws-0.0.1-SNAPSHOT.jar
