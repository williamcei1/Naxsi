https://github.com/nbs-system/naxsi/blob/master/README.md

##O que é o Naxsi?

NAXSI significa Nginx Anti Xss e SQL Injection

<p>
Tecnicamente, é um módulo a parte do nginx disponível em pacotes para diversas plataformas UNIX-like.
Este módulo, por padrão, lê um pequeno subconjunto de regras simples (naxsi_core.rules) contendo 99%
dos padrões conhecidos que envolva vulnerabilidades em sites. Por exemplo, '<', '|' ou 'drop' não devem ser parte de uma
URI.
</p>

<p>
Sendo muito simples, esses padrões podem corresponder consultas legítimas, é dever do administrador Naxsi adicionar regras
específicas WhiteList desses legítimos comportamentos. O administrador pode adicionar WhiteList manualmente por meio da
análise de erro de log do nginx, ou (recomendado) iniciar o projeto de uma fase de auto-aprendizado intensivo que irá 
gerar automaticamente regras WhiteList relativas ao comportamento do website.
</p>

<p>
Em resumo, Naxsi se comporta como um DROP padrão de firewall, o único trabalho necessário é adicionar regras exigidas 
ACCEPT  para o site de destino para funcionar corretamente.
</p>

##Por que é diferente?

<p>
Ao contrário de muitos Firewall de Aplicação Web, Naxsi não depende de uma base de assinatura, como um antivírus e, 
portanto,não pode ser contornado por um padrão de ataque "desconhecido". Outra principal diferença entre Naxsi e outros 
WAF, Naxsi filtra requisições Get & Posts e é OpenSource e de uso livre para sua empresa ou uso próprio pessoal 
(ou seja: enquanto você não revender um produto ou serviço baseado em Naxsi aos clientes).
</p>

##Introdução

Wiki

Veja a wiki

##Avaliações de Desempenho

	*Veja como Naxsi desempenha contra um site extremamente vulnerável
	*Veja como Naxsi desempenha vs Ofusca | padrões complexos de SQLI

##Precisamos de você!

	*Performance, teste de estabilidade: estamos procurando por opiniões independentes, pontos de referência e feedback 
	relacionado.
	*Testes de segurança: nós preparamos um ambiente de teste em execução para que você possa jogar. Vá, jogar, tente
	um Bypass!
	*Postar Solicitações de recursos , melhorias de documentação.
	*Relatar erros: Naxsi é novo, há erros conhecidos.




