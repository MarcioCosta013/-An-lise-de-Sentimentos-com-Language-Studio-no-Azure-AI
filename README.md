# Análise de Sentimentos com Language Studio no Azure AI

[Documentação Oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

### Analise texto com Language Studio

##### Crie um recurso de idioma

Você pode usar muitos recursos do Azure AI Language com um recurso de idioma ou de serviços do Azure AI . Existem alguns casos em que apenas um recurso Idioma pode ser usado. Para o exercício abaixo, utilizaremos um recurso Linguagem . Se ainda não o fez, crie um recurso de idioma na sua assinatura do Azure.

Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com , entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão **＋Criar um recurso** e pesquise Serviço de idioma . Selecione criar um plano de serviço de idiomas . Você será levado a uma página para selecionar recursos adicionais . Mantenha a seleção padrão e clique em Continuar para criar seu recurso .

Na página Criar Idioma , configure-o com as seguintes configurações:
- Assinatura : sua assinatura do Azure .
- Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .
- Região : Leste dos EUA.
- Nome : Insira um nome exclusivo .
- Nível de preços : F0 grátis ou S se F0 grátis não estiver disponível

Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .
Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.


![1](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/911fab07-a9e3-4718-9039-9e1acafb5231)

![2](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/4fbf73ef-e73a-4212-ba73-4dac8249b096)

![4](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/bff3973a-bc09-48ba-a553-52cf37654b19)

![5](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/bc10f916-bfbb-4de0-a523-a3961e2c8caf)

![6](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/5826b8d2-0e46-4ea1-be8e-1acadbc4a8b7)

![7](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/0e1a3c31-5c33-4c4d-85c9-a3952935b198)


### Configure seu recurso no Azure AI Language Studio

Em outra guia do navegador, abra o Language Studio em https://language.cognitive.azure.com e entre.

Quando solicitado com Select an Azure resource , faça as seguintes configurações:

- Diretório do Azure : diretório padrão, o diretório que você está usando
- Assinatura do Azure : selecione a assinatura que você está usando
- Tipo de recurso : Idioma
- Nome do recurso : selecione o recurso de serviço de idioma que você acabou de criar
  
Em seguida, selecione Concluído .

![3](https://github.com/MarcioCosta013/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/87935294/d490c68d-1c78-43b1-8b55-08109f3e1f16)





