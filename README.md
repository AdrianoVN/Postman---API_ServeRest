1 - Sobre o ServeRest

Todas as funcionalidades da API foram testadas com base na documentação Swagger: https://serverest.dev/

2 - Etapas e Considerações de Teste:

Verificação: Analise estática de cada funcionalidade descritas no swagger, e suas respectivas respostas.

Validação: Analise dinamica da execução do teste, o postman fornece alguns códigos (snippets) para validar todos os endpoints e se o sistema sendo construido de acordo com a documentação do swagger, como por momento não domino a linguagem JavaScript, utilizei a IA Copilot para sugerir e explicar os scripts para validar de maneira adequada e assim adapta-los a cada necessidade de teste

Extensão do Teste : Cobertura necessária de testes, visando a maior assertividade possível. Qualidade não é sinônimo de quantidade de casos de teste.

Profundidade do Teste: Características de qualidade do teste como melhorias.

3 - Considerações sobre os testes

Na minha percepção, avaliar de necessidade de trabalhar com dados fixos ou dinâmicos, para gerar massas de dados através de scripts Pré-Request, e determinar qual a melhor opção para execução dos testes. O Post-Response sendo obrigatório em todas as requisições na validação todos os testes, Por fim o fluxo das requisições (Request) seguem uma ordem lógica (CRUD) para serem executadas ordenadamente considerando uma automação.

(Create) criar os registros
(Read) ler os registros
(Update ) atualizar os registros
(Delete) excluir os registros do banco de dados.

4 - Relatório de Testes

Instalar o NodeJ: https://nodejs.org/en/download

Instalar o Newman: https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/

Instalar Reporter-htmlextra: https://www.npmjs.com/package/newman-reporter-htmlextra

