# Python BuscaCEP

#### Classe que possibilita a procura de endereço pelo CEP

Boa tarde pessoal, agora a pouco eu estava olhando os repositórios do github
quando eu me deparei com um repositório de uma programadora __JanainaCS04__
e um dos trabalhos dela foi o repositorio BuscaCEP, daí eu tive uma ideia
criar um em python, e como é de lei eu vou fazer a classe que realiza essa
busca e depois um exemplo de preferencia em *Tkinter* de um projeto visual
testando a classe Ok.

Vou tentar criar um pdf de como funciona a classe e também deixar aqui no
README uma pequena explicação , espero que gostem

#### Arquivo cep.py

Esse arquivo possui a classe __BuscaCEP__ que possibilita a qualquer pessoa
descobrir os dados de um CEP.

#### Bibliotecas utilizadas

    import requests - Responsável pela conexão com a base de dados

    from bs4 import BeautifulSoup - Responsável pela adequação dos dados

    import json - Responsável pela leitura dos dados

#### Classe BuscaCEP

A classe possui os seguintes metodos

    - init(CEP)
    - Buscar()
    - get_cep()
    - get_logradouro()
    - get_complemento()
    - get_bairro()
    - get_localidade()
    - get_uf()
    - get_ibge()
    - get_gia()
    - get_ddd()
    - get_siafi()

Os dois primeiros são os metodos de inicialização do objeto e os demais
são os metodos de retorno de informação.

#### Como usar ?
Não tem nenhum segredo utilizar essa classe só seguir os passos

__Decaração da classe__

    import cep

__Criar o objeto da classe__

    obj_cep = BuscaCEP(numero_CEP)
    obj_cep.Buscar()

__demais metodos__

    - get_cep() - retorna o CEP
    - get_logradouro() - retorna logradeouro 
    - get_complemento() - retorna complemento se houver
    - get_bairro() - retorna bairro
    - get_localidade() - retorna localidade
    - get_uf() - retorna UF
    - get_ibge() - retorna dados ibge
    - get_gia() - retorna gia
    - get_ddd()- retorna ddd
    - get_siafi()- retorna dados siafi 