# API-CEP

API REST para consulta de CEP.

# Arquitetura da Aplicação
* Golang
* Go Modules
* Struct
* Server mux
* net/HTTP
* JSon
* Git

# Aplicação
Consulta de CEP utilizando a concorrência do Go para realizar diversas requisições simultâneas para cada um dos serviços de CEP e pegar a resposta dos serviços que responderem mais rapidamente.
* Postmon
* Republic Virtual
* ViaCep

# Servidor
http://localhost:4000/cep/{cep}

Executando no Terminal
* go run main.go