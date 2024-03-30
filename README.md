
# ssh-lzma-backdoor

  

Ontem(2024-03-29) foi descoberta uma tentativa de implantar um backdoor em uma dependência do SSH

  

# Informações sobre o caso

  

## publicação

https://www.openwall.com/lists/oss-security/2024/03/29/4

  

## Vídeo

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/jqjtNDtbDNI/0.jpg)](https://www.youtube.com/watch?v=jqjtNDtbDNI)

  

## Conclusão

  

Em resumo não há sistemas estáveis comprometidos. Os sistemas baseados em repositórios instáveis (de lançamento recente) ou de testes podem conter o backdoor. Na própria postagem o autor publicou um script para detectar se o sistema está comprometido. Se o script indicar "probably vulnerable" tente atualizar o SSH mais precisamente o pacote xz-utils na versão 5.6.


## Mais sobre

https://cert.europa.eu/publications/security-advisories/2024-032/

