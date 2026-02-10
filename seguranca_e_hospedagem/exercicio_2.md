## 🧠 Questões Teóricas sobre DNS

**1.** **O que significa a sigla DNS e qual é sua principal função?**

  DNS significa Domain Name System; sua função é traduzir nomes de domínio em endereços IP.

**2.** Por que o DNS foi criado? Qual problema ele resolveu na Internet?

  Foi criado para evitar o uso de IPs numéricos, facilitando o acesso a sites por nomes.
  
**3.** O que é um nome de domínio? Dê um exemplo.

  É o nome que identifica um site na Internet, como www.google.com.

**4.** Qual é a função de um servidor DNS? 

  Resolver nomes de domínio, convertendo-os em endereços IP.

**5.** Cite dois tipos de registros DNS e explique brevemente um deles.

  A: aponta um domínio para um endereço IPv4.
  MX: define servidores de e-mail de um domínio.

## 🪟 Questões sobre DNS no Windows

**6.** Qual comando do Windows é utilizado para testar a resolução de nomes DNS?

  nslookup

**7.** Para que serve o comando `ipconfig /all` em relação ao DNS?

  Mostra as configurações de rede, incluindo servidores DNS usados.

**8.** Qual comando pode ser usado para limpar o cache DNS no Windows?

  ipconfig /flushdns

**9.** Onde o Windows armazena temporariamente as informações de DNS?

  No cache DNS da memória do sistema.

**10.** Ao acessar um site no Windows e ocorrer erro de DNS, cite uma possível causa.

  Servidor DNS incorreto ou indisponível.
  
## 🐧 Questões sobre DNS no Linux

**11.** Qual arquivo do Linux contém os servidores DNS configurados no sistema?

  /etc/resolv.conf

**12.** Qual comando pode ser usado no Linux para consultar registros DNS de um domínio?

  dig ou nslookup

**13.** Para que serve o comando `ping` em relação ao DNS? 

  Testa a resolução de nomes e a conectividade com o host.

**14.** Qual a função do arquivo `/etc/hosts` no processo de resolução de nomes?

  Faz a resolução local de nomes antes de consultar o DNS.

**15.** Cite uma diferença básica entre a configuração de DNS no Windows e no Linux.

  No Windows a configuração é feita via interface gráfica; no Linux, via arquivos de texto.
