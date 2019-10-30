# Analista
Desafio proposto: 
• Aplicação WEB/PHP na versões mais atuais. Poderá trabalhar com aplicações prontas como qualquer CMS padrão de mercado, porém o diferencial será integrar uma base ldap local como autenticação primária do mesmo; 
• Monitoramento proativo de aplicação, banco de dados e sistema operacional; 
•Base ldap para autenticação primária da solução de monitoramento e web. Diferencial: Aplicação para gerenciamento WEB da base LDAP;. 
• Segurança: a) Política padrão DROP para as chains INPUT, FORWARD e OUTPUT; b) Stateful; c) Apenas http/https disponíveis; d) Diferencial: ssh via port knocking e/ou vpn; 

Itens da Solução

 * Como aplicação WEB/PHP, como sugerido foi utilizado o WORPRESS 
 • Active Directory Integration / LDAP Integration como intermediário da integração da base LDAP com a Aplicação WEB/PHP. 
 • Banco de dados MYSQL/ MAriaDB 
 • Servidor Apache 2.4.6 
 • PHP 5.6 (Devido alguns bugs que estavam ocorrendo) 
 • Servidor OpenLdap na sua última versão 
 • PHPLdapAdmin para Gerenciamento web da base LDAP. 
 • ZABBIX para monitoramento do Sistema e Banco de Dados. 
