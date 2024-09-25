# resumo-do-lab
Resumo do aprendizado durante o desenvolvimento do lab na DIO

# Introdução ao Azure: Aprendizado sobre Conceitos Iniciais e Certificação AZ-900

O foco do curso é a introdução ao Azure, com ênfase nos conceitos iniciais essenciais para a certificação AZ-900. Um dos principais tópicos abordados é a computação em nuvem, que envolve o fornecimento de diversos serviços de computação, incluindo bancos de dados, servidores de arquivos e muito mais.

## Modelos de Nuvem

### Nuvem Privada

O modelo de nuvem privada refere-se a um servidor próprio da empresa, onde todos os custos de criação, operação e manutenção são de responsabilidade interna. Embora esse investimento inicial possa diminuir ao longo do tempo, a previsibilidade dos custos é menor em comparação com o modelo de nuvem pública. Além disso, o acesso a uma nuvem privada é limitado apenas aos usuários da organização.

### Nuvem Pública

Na nuvem pública, uma empresa externa se encarrega de fornecer o serviço, garantindo a criação, operação e manutenção. Essa abordagem permite que os custos sejam cobrados de acordo com o uso, facilitando a determinação dos gastos operacionais. A nuvem pública também oferece vantagens significativas em termos de escalabilidade, permitindo que a aplicação seja facilmente adaptada a novas necessidades. Modificações podem ser feitas rapidamente, e ambientes podem ser provisionados ou desprovisionados sem complicações.

### Nuvem Híbrida

O modelo híbrido combina elementos da nuvem privada e da nuvem pública. Com essa abordagem, a empresa pode determinar o local onde os dados serão armazenados e como as aplicações serão executadas, proporcionando maior flexibilidade. Essa combinação permite que as organizações tirem proveito das vantagens de ambos os modelos, otimizando custos e controlando melhor suas operações.

## Considerações Financeiras

No contexto da computação em nuvem, é importante entender a diferença entre CapEx e OpEx.

- **CapEx (Custo de Capital)** refere-se aos investimentos em estrutura física, como servidores e data centers.
- **OpEx (Despesas de Operação)** abrange os custos recorrentes associados ao funcionamento e à manutenção dos serviços.

Esse aprendizado sobre os conceitos iniciais de computação em nuvem e os diferentes modelos disponíveis proporciona uma base sólida para compreender as práticas e as estratégias envolvidas na implementação de soluções em Azure, preparando-me para a certificação AZ-900.

### PARTE 2:

### Escalabilidade
A escalabilidade reforça o conceito já aprendido e refere-se à capacidade de aumentar o poder computacional. Ela pode ser feita de duas maneiras: **vertical**, aumentando os recursos de uma única instância, ou **horizontal**, criando mais subdivisões com divisão de responsabilidade, permitindo a distribuição da carga de trabalho.

### Elasticidade
A elasticidade é a capacidade de rapidamente expandir a capacidade do servidor em picos de uso repentino, seja de forma manual ou automática.

### Confiabilidade
A confiabilidade é a capacidade de minimizar problemas de falta de operação, geralmente garantida pela escalabilidade horizontal. Isso significa que, ao aumentar o número de instâncias, podemos manter a operação estável mesmo diante de falhas.

### Previsibilidade
Os serviços ofertados têm métricas e informações que garantem a confiança em sua adoção, contribuindo para a previsibilidade dos custos e da performance.

### Segurança
A nuvem oferece acesso a ferramentas de segurança, e é importante que sua implementação seja feita pela empresa para proteger os dados e as aplicações.

### Governança
A governança está relacionada com monitoramento e auditoria para garantir que a aplicação funcione conforme os requisitos e políticas da empresa, essencial para manter a conformidade e a segurança.

## PARTE 3:

### Tipos de Serviço

- **IaaS (Infrastructure as a Service)**: Relacionado à infraestrutura, é o que mais abordaremos nessa área. Então, estamos falando de máquinas virtuais, servidores, etc.
  
- **PaaS (Platform as a Service)**: Relacionado à plataforma, engloba a infraestrutura e adiciona sistemas operacionais e ferramentas para desenvolvedores. Tira um pouco o foco do gerenciamento da infraestrutura e foca no acesso a uma determinada aplicação ou serviço, como um servidor de banco de dados.

- **SaaS (Software as a Service)**: Assim como o PaaS, este modelo engloba IaaS e PaaS, adicionando agora aplicativos hospedados. Geralmente se refere a serviços como o Office 365, onde o uso é sob licença.

Então eu poderia resumir em:
- **IaaS**: Eu quero uma infraestrutura para eu poder utilizar para a minha aplicação; quero gerenciar tudo.
- **PaaS**: Apenas quero fazer uma determinada aplicação, mas não quero me importar com como será a infra.
- **SaaS**: Eu apenas quero utilizar uma aplicação já existente.

### Modelo de Responsabilidade Compartilhada
O modelo de responsabilidade compartilhada é basicamente uma tabela que indica quais responsabilidades (da Microsoft, do cliente, compartilhadas) estão atreladas a quem de acordo com o tipo de serviço (SaaS, PaaS e IaaS). Isso é crucial para entender onde a empresa deve se concentrar na segurança e na gestão dos serviços.

### Gerenciabilidade
A gerenciabilidade diz respeito à facilidade de gerenciar recursos da nuvem, incluindo a capacidade de monitorar, configurar e otimizar os serviços de forma eficiente.

Boa parte dos conceitos apresentados foram citados na primeira parte, mas agora estão um pouco aprofundados no contexto de listar benefícios do serviço de nuvem.
