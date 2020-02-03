# java-for-web-cap7-cad-contas-ajax

01-30-20 

Início

1 - Criacao da classe conta
    package  br.com.javaparaweb.financeiro.conta
    class Conta
2 - hibernate.cfg.xml 
    <mapping class="br.com.javaparaweb.financeiro.conta.Conta"/>
3 - Criação da interface ContaDAO
4 - Alteração da classe DAOFactory
    adicionado o metodo criarContaDAO()
5 - Construcao da camada de regra de negocios
    classe ContaRN