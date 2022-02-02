# Projeto

 {

Class dicionario():
 dicionario = {

  "nome": "Marcela",

  "sobrenome": "Freitas",

  "idade": 7

}

dicionario["nome"] # Marcela

dicionario["idade"] # 7

dicionario["rua"] # KeyError: 'rua'

dicionario.get("rua") # None
for chave in dicionario:

  print(dicionario[chave])

    for valor in dicionario.values():

  print(valor)

    for chave, valor in dicionario.items():

  print(chave, valor)
   if "nome" in dicionario:

  print("Nome: " + dicionario["nome"])

    len(dicionario) #3
    dicionario = {}

dicionario["marca"] = "Mercedez"

dicionario["modelo"] = "Classe A"

dicionario.pop("modelo")
  contatos = {

  "Flávia" : {

      "nome": "Flávia",

        "telefone": "99234-1234",

        "email": "flavia@email.com"

        },

    "Daniela Sato": {

      "nome": "Daniela Sato",

        "telefone": "7658-2091",

        "email": "daniela.sato@enterprises.com",

        "empresa": "Enterprises"

        }

    }  

    comando = "continue"

contatos = {}
while comando != "sair":

  comando = input("Digite o comando: (novo, pes, sair):")
  if comando == "novo":

    nome = input("Nome: ").strip()

    telefone = input("Telefone: ").strip()

    email = input("E-mail: ").strip()

    contatos[nome] = {

      "nome": nome,

      "telefone": telefone,

      "email": email

    }

    if comando == "pes":

  nome = input("Nome: ").lower()

    if nome in contato:

      contato = contatos[nome]

      print(contato)

    else:

      print("Não encontrado")

      }
