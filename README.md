# Buscas-Cognitivas-Azure-IA

1. Acesse a página inicial da azure no link: https://portal.azure.com, pesquise por "Azure AI Search" no buscador e clique em "Pesquisa de IA".
![Página Inicial da Azure](images/img-1.jpg)

<br>

2. Na nova aba clique em "Criar" no menu de opções, para criar um novo recurso de pesquisa.
![Menu lateral da Azure](images/img-2.jpg)

<br>

3. Em "Detalhes do projeto", não altere a opção de assinatura. Em "Grupo de recursos" escolha um já criado ou crie um novo no botão abaixo "Criar novo".
![Detalhes do projeto](images/img-3.jpg)

<br>

4. Descendo a tela, temos os detalhes da instância, coloque um nome de sua preferência. É recomendado não utilizar servidores da região do Brasil, por questões de instabilidade, aqui utilize a já indicada pela Azure ou "West US 2". Em "Camada de preço" clique na opção "Alterar o Tipo de preço".
![Detalhes da instância](images/img-4.jpg)

<br>

5. Clique na opção "Basico" e depois clique em "Selecionar".
![Botão Examinar + Criar](images/img-5.jpg)

<br>

6. Revise tudo e clique no botão "Revisar + criar" na lateral inferior esquerda
![Botão Examinar + Criar](images/img-6.jpg)

<br>

7. Você será redirecionado a outra página com os termos, clique em "Criar" na lateral inferior esquerda
![Tela Examinar + Criar](images/img-7.jpg)

<br>

8. Após ser redirecionado, deve aparecer um card de exito. Volte a tela inicial da Azure.
![Tela de implantação concluida](images/img-8.jpg)

<br>

9. Clique em "Criar um recurso".
![Página Inicial da Azure](images/img-9.jpg)

<br>

10. No menu de opções na lateral esquerda, clicar em "IA + Machine Learning".
![Menu lateral da Azure](images/img-10.jpg)

<br>

11. Na opção "Serviços Cognitivos" clicar em "Criar".
![Serviços Cognitivos da Azure](images/img-11.jpg)

<br>

12. Em "Detalhes do projeto", não alterar a opção de assinatura. Em "Grupo de recursos" escolha um já criado ou crie um novo no botão abaixo "Criar novo".
![Detalhes do projeto](images/img-12.jpg)

<br>

13. Descendo a tela, temos os detalhes da instância, é recomendado não utilizar servidores da região do Brasil, por questões de instabilidade, aqui utilize a já indicada pela Azure ou "East US". Em "Nome" coloque um nome de sua preferência. Em "Tipo de preço" escolha a opção padrão (Standard S0). E confirme a checkbox sobre os preços abaixo.  
![Detalhes da instância](images/img-13.jpg)

<br>

14. Revise tudo e clique no botão "Examinar + criar" na lateral inferior esquerda
![Botão Examinar + Criar](images/img-14.jpg)

<br>

15. Você será redirecionado a outra página com os termos, clique em "Criar" na lateral inferior esquerda
![Tela Examinar + Criar](images/img-15.jpg)

<br>

16. Após ser redirecionado, deve aparecer um card de exito. Volte a página inicial da Azure.
![Tela de implantação concluida](images/img-16.jpg)

17. Pesquise por "Storage Account" no buscador e clique em "Contas de armazenamento".
![Página Inicial da Azure](images/img-17.jpg)

<br>

18. Clique em "Criar" na aba de opções para criar uma nova conta de armazenamento.
![Página Inicial da Azure](images/img-18.jpg)

<br>

19. Em "Detalhes do projeto", não altere a opção de assinatura. Em "Grupo de recursos" escolha um já criado ou crie um novo no botão abaixo "Criar novo".
![Página Inicial da Azure](images/img-19.jpg)

<br>

20. Descendo a tela, temos os detalhes da instância, coloque um nome de sua preferência. É recomendado não utilizar servidores da região do Brasil, por questões de instabilidade, aqui utilize a já indicada pela Azure ou "East US". Em "Desempenho" selecione a opção "Standard", em "Redundância" esolha a opção "LRS". Por fim clique em "Examinar".
![Menu lateral da Azure](images/img-20.jpg)

<br>

21. Examine tudo e clique em "Criar".
![Menu lateral da Azure](images/img-21.jpg)

<br>

22. Após ser redirecionado, deve aparecer um card de exito. Clique no botão "Ir para o recurso".
![Menu lateral da Azure](images/img-22.jpg)

<br>

23. Na barra de navegação lateral, encontre a opção "Configuração" e clique nela.
![Menu lateral da Azure](images/img-23.jpg)

<br>

24. Habilite a opção "Permitir acesso anônimo ao Blob" e clique em Salvar na barra de opções.
![Menu lateral da Azure](images/img-24.jpg)

<br>

25. Na barra de navegação lateral, encontre a opção "Contêineres" e clique nela.
![Menu lateral da Azure](images/img-25.jpg)

<br>

26. CLique em "Contêiner" para criar um novo Contêiner.
![Menu lateral da Azure](images/img-26.jpg)

<br>

27. No campo "Nome", escolha um nome de sua preferência. No campo "Nível de acesso anônino" escolha a opção "Contêiner". E por fim clique em "Criar".
![Menu lateral da Azure](images/img-27.jpg)

<br>

28. Acesse a documentação oficial da Microsoft em: https://aka.ms/ai900-ai-search. Vá até a seção "Carregar documentos para o armazenamento do Azure"
![Menu lateral da Azure](images/img-28.jpg)

<br>

29. Encontre a seção 4 do tópico e aperte no link "avaliações de café compactadas", ele deve iniciar um download no seu navegador, abra a pasta após concluir o download no seu explorador de arquivos.
![Menu lateral da Azure](images/img-29.jpg)

<br>

30. Descompacte a pasta, volte a Azure e selecione o contêiner criado.
![Menu lateral da Azure](images/img-30.jpg)

<br>

31. Clique em "Carregar" e faça upload da pasta baixada.
![Menu lateral da Azure](images/img-31.jpg)

<br>

32. Confirme a inserção dos arquivos clicando em "Carregar".
![Menu lateral da Azure](images/img-32.jpg)

<br>

33. Volte ao mecânismo de busca criado anteriormente.
![Menu lateral da Azure](images/img-33.jpg)

<br>

34. Clique em "Importar dados".
![Menu lateral da Azure](images/img-34.jpg)

<br>

35. Ao abrir o import de dados selecione a opção "Armazenamento de Blob do Azure".
![Menu lateral da Azure](images/img-35.jpg)

<br>

36. Na seção "Conectar a seus dados", mantenha a "Fonte de Dados", dê um nome de sua escolha a fonte de dados, mantenha a opção "Contéudo e metadados" em "Dados para extrair", em "Modo de análise" mantenha o padrão e por fim clique em "Escolher uma conexão existente" para o campo "Cadeia de conexão".
![Menu lateral da Azure](images/img-36.jpg)

<br>

37. Ele deve exibir a cadeia criada anteriormente, selecione e clique em "Selecionar".
![Menu lateral da Azure](images/img-37.jpg)

<br>

38. Ele deve se autocompletar após selecionar o armazenamento criado.
![Menu lateral da Azure](images/img-38.jpg)

<br>

39. Continuando, em "Autenticação de identidade gerenciada" escolha "Nenhum", em "Nome do contêiner" escolha o contêiner criado, não é necessário preencher "Pasta de blobs" nem "Descrição" (Opcional). Por fim clique em "Próximo: Adicionar habilidades cognitivas (opcional)".
![Menu lateral da Azure](images/img-39.jpg)

<br>

40. Expanda a seção "Adicionar enriquecimentos".
![Menu lateral da Azure](images/img-40.jpg)

<br>

41. Defina um nome de sua escolha, habilite a checkbox para habilitar o OCR. Certique-se que a opção marcada para "Campos de dados de origem" esteja em "merged_content". E em "Nível de granulidade do enriquecimento" escolha a opção "Páginas (parte de caracteres de 5000)". Deixe "Habilitar o enriquecimento incremental" em branco.
![Menu lateral da Azure](images/img-41.jpg)

<br>

42. Continuando, em "Habilidades Cognitivas de Texto", assinale as opções: "Extrair nomes de localização", "Extrair frases-chave" e "Detectar sentimento". Em "Habilidades Cognitivas de Imagem", assinale todas as opções.
![Menu lateral da Azure](images/img-42.jpg)

<br>

43. Continue para a seção "Salvar os enriquecimentos em um repositório de conhecimento", escolha "Escolher uma conexão existente".
![Menu lateral da Azure](images/img-43.jpg)

<br>

44. Escolha uma conta de armazenamento existente.
![Menu lateral da Azure](images/img-44.jpg)

<br>

45. Selecione o contâiner criado.
![Menu lateral da Azure](images/img-45.jpg)

<br>

46. Assinale todas as opções (o nome do contêiner será preenchido automáticamente), por fim clique em "Próximo: Personalizar índice de destino".
![Menu lateral da Azure](images/img-46.jpg)

<br>

47. Na seção "Personalizar índice de destino", defina o nome de sua escolha, em "Chave" defina como "metadata_storage_path", deixe a opção "Nome do sugestor" em branco e deixe a opção "Modo de busca" como está.
![Menu lateral da Azure](images/img-47.jpg)

<br>

48. Abaixo, selecione todos os campos já selecionados como "Filtrável" e clique em "Próximo: Criar um indexador".
![Menu lateral da Azure](images/img-48a.jpg)
![Menu lateral da Azure](images/img-48b.jpg)

<br>

49. Na seção "Criar um indexador", defina um nome de sua preferência e em agenda escolha "Uma vez".
![Menu lateral da Azure](images/img-49.jpg)

<br>

50. Expanda a seção "Opções avançadas", assinale a opção "Chaves de Codificação de Base 64" e clique em "Enviar".
![Menu lateral da Azure](images/img-50.jpg)

<br>

51. Voltando no recurso do serviço de pesquisa, em "Gerenciador de pesquisa".
![Menu lateral da Azure](images/img-51.jpg)

<br>

52. Faça uma busca clique em "Pesquisar" e veja que na seção "Resultado", temos a resposta da pesquisa em um formato JSON.
![Menu lateral da Azure](images/img-52.jpg)

<br>