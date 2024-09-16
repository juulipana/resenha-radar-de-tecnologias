**Resenha do Artigo ‘Technology Radar’: Um Guia de Opinião sobre o Universo da Tecnologia Atual**

O artigo *Technology Radar*, desenvolvido pela Thoughtworks, oferece um mapeamento das tecnologias emergentes, analisando-as e classificando-as de acordo com sua confiabilidade. O objetivo principal do radar é identificar tecnologias promissoras e fornecer uma avaliação de como e onde elas podem ser utilizadas com no desenvolvimento de software. O radar é dividido em quatro anéis que refletem o nível de confiança em cada tecnologia:

- **Adote**: Ferramentas que a indústria deve adotar.
- **Experimente**: Tecnologias que merecem ser testadas em projetos com risco controlado.
- **Avalie**: Tecnologias promissoras que ainda precisam ser compreendidas em maior profundidade.
- **Evite**: Ferramentas ou práticas que devem ser usadas com cautela.

Nesta resenha, focamos apenas nas tecnologias **Adote**, que são consideradas mais confiáveis e recomendadas para uso em projetos. As tecnologias destacadas são: **RAG (Geração Aumentada por Recuperação)**, **Conan**, **Kaniko** e **Karpenter**.

### Geração Aumentada por Recuperação (RAG)
A **Geração Aumentada por Recuperação (RAG)** é uma técnica usada para melhorar a qualidade das respostas de modelos de linguagem de grande porte (LLMs). RAG reduz o risco de *alucinações* (respostas incorretas ou irrelevantes) ao integrar informações relevantes armazenadas em bancos de dados. Para isso, ao receber um comando ou pergunta, o sistema consulta esses documentos, seleciona os mais relevantes e os utiliza levando em conta o contexto fornecido ao modelo de linguagem, resultando em respostas mais precisas. É amplamente utilizada em plataformas de IA.

### Conan
**Conan** é uma ferramenta para o gerenciamento de dependências em projetos C e C++. Ela simplifica a busca, definição e gerenciamento de bibliotecas e pacotes do desenvolvimento de projetos, garantindo que todas as dependências sejam configuradas corretamente. Isso resulta em um ambiente de desenvolvimento mais limpo e rápido, além de tornar o processo de compilação mais eficiente, especialmente para projetos de grande escala. Conan também se integra facilmente com sistemas de build como o CMake, o que acelera o tempo de compilação.

### Kaniko
**Kaniko** é uma ferramenta projetada para construir imagens Docker em pipelines de containers. Um pipeline é uma sequência automatizada de processos que compila, testa e implanta software, garantindo que cada etapa seja realizada de forma eficiente e repetível. O Kaniko se destaca por permitir que essas imagens sejam construídas diretamente em ambientes que não têm acesso do Docker, como ambientes em nuvem ou clusters Kubernetes.

### Karpenter
**Karpenter** é uma ferramenta open source voltada para o autoescalamento de nós em clusters Kubernetes. Um *workload* é um conjunto de aplicações ou processos que um sistema precisa gerenciar e executar. O Kubernetes é uma plataforma usada para automatizar o gerenciamento de containers e escalá-los conforme uma demanda. O Karpenter ajuda a otimizar esse processo analisando as necessidades do sistema e automatizando a liberação de recursos necessários para manter o desempenho. Ele garante que o ambiente tenha sempre os recursos preparados.
