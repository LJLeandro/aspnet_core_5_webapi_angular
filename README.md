Para Executar esse Sistema é preciso rodar localmente uma imagem Docker SQL Server
     $ docker pull mcr.microsoft.com/mssql/server
     $ docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=appnetangular12345$444 -e "MSSQL_PID=Express" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest 
