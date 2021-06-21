# Teste-Compasso_
Responda as questões abaixo de forma clara e objetiva, quando necessário pode ser adicionado uma documentação de apoio (read-me).
**1.	Gherkin - montar um mapa mental e criar cenários de um fluxo de compra
(Ferramenta de elaboração do mapa de livre escolha, anexar no formato de imagem)**
Anexo: Mapa Mental 
1. Validação da interface inicial 	
2. Validação das classificações de produto	
3. Validaçao de Pesquisa dos Produtos	
4. Validaçao das descrições de venda de produto	
5. Validação de dados de estoques de produto	
6. Validação de Inclusão de Produtos na Sacola	
7. Validação do Calculo de Frete	
8. Validação de informações de endereço	
9. Validação de exclusão de produtos na sacola	
10. Validação de finalização de compra 	
11. Validação de continuação de compra	
12. Validação de Cadastro de usuário 	
13. Validação de Login e senha do usuário	
14. Validação de login com Facebook e Google	
15. Validação de Tipos de Pagamentos 	
16. Validação de formas de parcelamento	
17. Validação de Comprovante de compras 	
18. Validação de envio de confirmação de compra por email	
19. Validação de Fluxo de Pedidos 	

**2.	Testes de prático de APIs – Elaborar um fluxo de cadastro/validação de campos/ listar cadastro – utilizar APIs públicas 
(anexar informações de como testar, json, url, etc...)**
Anexo: Teste de API.postman_collection.json
URL: https://petstore.swagger.io/
1) Cadastrei a usuaria Maria Assunção
2) Cadastrei o pet Brutus (dog)
3) Fiz a venda do Brutus para a Maria Assunção
4) Mudei o status da ordem de venda do Brutus para "delivered"
5) Consultei a ordem gerada e validei se estava correta
6) Cadastrei 5 usuários e 10 pets (5 dogs e 5 cats)
7) Fiz a venda de 1 dog e 1 cat para cada usuário
8) Mudei o status das ordens de venda de dogs para "delivered" e de cats para "approved"

**3.	Estratégia de Testes para e-commerce - definir e escrever os primeiros passos/condução/tramitação dos testes em um e-commerce
(e-commerce de livre escolha, sugestão verificar no site da compasso o portifólio de clientes e escolher um deles)**
Anexo: Caso de testes (OBS: No anexo de excel tem as abas "Fluxo de compras / Teste de Navegação e página de produto / Teste de Checkout) 


**4.	Priorização de execução de testes
Explicar o processo de priorização da execução de testes, apontar a sequência e explicar por que foi escolhida.**
1. Análise de requisitos: Nesse caso não pude ter contato com o cliente para alinhar com ele as suas principais necessidades, mas coloquei meu ponto de vista técnico para simular as principais necessidades que um cliente teria. 
2. Realização do planejamento: Realizei o Planejamento para selecionar minhas metas e objetivos que seria o projeto do cliente e qual abordagem eu iria utilizar para os testes. 
3. Configuração do ambiente de teste: Verifiquei quais as arquiteturas iria utilizar para configurar o ambiente e verifiquei quais seriam os requisitos. 
4. Implementação: Identifiquei, evidenciei, desenvolvi, finalizei, implementei e priorizei os casos de testes. Executei os procedimentos de testes baseado em priorização. Poderia identificar defeitos e nesse caso reportaria o defeito, refaria o teste, realizaria o teste de regressão. 
5. Encerramento: Chequei se tudo que foi planejado foi entregue. Evidenciei o resultado. Fecharia os incidentes e relatórios caso fossem abertos. A partir desse ciclo verifiquei o que poderia ser melhorado para a maturidade de um futuro projeto. 

**5.	KPIs importantes para os testes e-commerce
Apontar quais são os KPIs mais importantes relacionados a testes em e-commerce.**
R: Em primeiro lugar é importante levantar com cliente as suas principais prioridades. No ponto de vista técnico é importante considerar as probabilidades e a relevância de cada funcionalidade e a questão da regra do sistema que será realizado o teste, pois é preciso saber a severidade do impacto causado por um erro no negócio do cliente. 
1)	Teste de navegação: É muito importante explorar o layout da home de dos demais itens que pode facilitar a compra para um usuário. 
2)	Página de Produtos: É importante que a percepção do produto esteja o mais claro possível para o usário. Dessa forma é importante realizar os diversos testes explorando todos os itens realacionado ao produto. 
3)	Login e Cadastro de um usário: É importante que os usuários tenham facilidade em realizar seu cadastro ou em se logar para conseguir realizar um compra e ter acessos a informações internas. 
4)	Página de Checkout: É importante verificar todos os scripts que estão relacionados a pagamento, pois a realização de uma compra sem se deparar com problemas, melhoram a experiência do usário. 
