# PUC-INF1408
Disciplina Análise de Processos

Escopo
O escopo limita o sistema em projeto. Tipicamente, um caso de uso descreve o uso de um sistema de software; nesse caso ele é conhecido como um caso de uso de sistema. Num escopo mais amplo, os casos de uso podem também descrever como um negócio é usado por seus clientes e sócios. Tal descrição de processo no nível de empresa é chamado de caso de uso de negócio e é um bom exemplo da ampla aplicabilidade de casos de uso, mas eles não são abordados neste livro introdutório.


Nível
No sistema de Cockburn, os casos de uso são classificados como estando no nível de objetivo do usuário ou no nível de subfunção, entre outros. Um caso de uso no nível de objetivo do usuário é o tipo comum que descreve os cenários para atingir os objetivos de um ator principal para conseguir que um trabalho seja feito; corresponde aproximadamente a um processo elementar de negócio na engenharia de processos de negócio. Um caso de uso no nível de subfunção descreve subpassos necessários para apoiar um objetivo de usuário e é geralmente criado para individualizar subpassos duplicados compartilhados por diversos casos de uso regulares (para evitar duplicar texto comum); um exemplo é o caso de uso de subfunção Pagar a Crédito, que pode ser compartilhado por muitos casos de uso regulares.


Ator principal
O ator principal que procura os serviços do sistema para atingir um objetivo

Lista de interessados e interesses - Importante!
Essa lista é mais importante e prática do que pode, a princípio, parecer. Ela sugere e limita o que o sistema deve fazer. Citando um exemplo:
"O [sistema] opera um contrato entre os interessados, com os casos de uso detalhando as partes comportamentais desse contrato...O caso de uso, como contrato para comportamento, capta todos e somente os comportamentos relacionados à satisfação dos interesses dos interessados [Cockburn01]."
Issso responde a questão: o que deve constar no caso de uso? A resposta: o que satisfaz todos os interessados. Além disso, começando com os interessados e seus interesses antes de redigir o resto do caso de uso, temos um método para nos lembrar quais deveriam ser as responsabilidades mais detalhadas do sistema. Por exemplo, eu teria identificado uma responsabilidade para tratar a comissão de um vendedor se não tivesse primeiro listado o interessado vendedor e seus interesses? Espero que sim, mas talvez não tivesse notado isso durante a primeira sessão de análise. O ponto de vista do interessado fornece um procedimento abrangente e prático para cobrir e registrar todos os componentes requeridos.
