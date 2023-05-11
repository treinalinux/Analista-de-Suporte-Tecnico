# Criando e Geranciando Hosts Virtuais no VirtualBox

## 1 - Criando um Host Red Hat Enterprise Linux

Escolha uma versão do Red Hat Enterprise Linux, baixe instale de acordo com os requistos técnicos mínimos recomendados pelo site oficial.

**Dica:** A maior parte das documentções chega primeiro em inglês, então pesquise no Google *How to SEU_ASSUNTO_PESQUISADO_INGLES*

Eu fiz uma pesquisa **"how to install red hat enterprise linux 8 requirements minimum"**, e encontrei o link: [System requirements reference](https://access.redhat.com/documentation/pt-br/red_hat_enterprise_linux/8/html/performing_a_standard_rhel_8_installation/system-requirements-reference_installing-rhel)

Eu poderia deixar o que diz no site abaixo, mas você é a pessoa quem vai criar o recurso com base na sua pesquisa. Então, acesse o link ou pesquise pelo termo.

Boa sorte.

### 1.1 - Orientações do Sistema

Siga as orientações do sistema para o sistema escolhido por você:

- Deve fazer parte de sua rede local, com algum IP disponível fixo da sua rede, exemplo: 192.168.1.0/24 (Endereço de rede)
 - No Windows ipconfig /all, retorna o seu IP atual, se existir no Linux (ip a) ou no MacOS use ifconfig
- O nome para o seu host virtual de ser rhel-NUMERO_DA_VERSAO_ESCOLHIDA.empresa.corp
- No arquivo /etc/selinux/config desabilite o SELinux, por equanto.

Boa sorte.
