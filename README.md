#trabalhando com Tuplas
diasDaSemana = (
  "Domingo",
  "Segunda-Feira",
  "Terça-Feira",
  "Quarta-Feira",
  "Quinta-Feira",
  "Sexta-Feira",
  "Sábado",
  
)
print(diasDaSemana)
#O acesso a itens é igual ao Array (listas)
print(diasDaSemana[0])
print(diasDaSemana[-1]) #ultimo item
#Loop em uma tupla - igual ao Array
for umDia in diasDaSemana:
    print(umDia)
#Tuplas nao podem ser modificadas
#diasDaSemana[0] = "Primeira-feira"
#essa tentativa gerará erro
#medindo tamanho de uma tupla - igual ao Array
print(len(diasDaSemana))
#verificando ocorrencias em uma tupla
print(diasDaSemana.__contains__("Sábado"))
#trabalhando com dicionario e o par [Chave : Valor]
capitais = {
  "Goiás" : "Santa Rita",
  "Santa Catarina" : "Florianópolis",
  "Bahia" : "Salvador"
}
print(capitais)
#Acessando um valor em um dicionario
print(capitais["Bahia"])
#acessando todas as chaves
print(capitais.keys())
#acessando todos os valores
print(capitais.values())
#modificando valores 
capitais["Goiás"] = "Goiânia"
print(capitais)
#adicionando valores
capitais["Maranhão"] = "São Luís"
print(capitais)
#removendo uma chave e um valor
capitais.pop("Maranhão")
print(capitais)
#verificando se o dicionario tem uma chave especifica
print(capitais.__contains__("Bahia"))
