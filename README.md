MBA em Desenvolvimento FullStack pela IGTI e Analista de desenvolvimento de sistemas pela UNIP.

✨ Dicas especiais aqui no Git. 



Docker Compose

///Parar e Excluir todos os containers
sudo docker system prune -a --volumes


Botao direito emcima de docker-compose.yml e selecionar a opcao Compose Up


Dbeaver 

Navigate to Driver Properties: Click on the Driver properties tab (next to the "Main" tab).
Enable Retrieval:

    Find the property named allowPublicKeyRetrieval.
    Change its value from false to true


Alternative (SSL Tab): In newer versions of DBeaver, you can also go to the SSL tab and check the "Allow public key retrieval" box.


Disable Certificate Verification (Quick Fix) 
If you are in a development environment and do not need strict SSL validation:

    Right-click your connection > Edit Connection.
    Navigate to SSL settings.
    Uncheck Verify server certificate.
