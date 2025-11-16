🧼 Clean Architecture — Estudos e Práticas

Este repositório reúne meus estudos sobre Clean Architecture, abordando desde conceitos fundamentais até aplicações práticas. Apesar de já trabalhar há mais de 2 anos utilizando Clean Architecture no desenvolvimento backend, decidi aprofundar ainda mais meu entendimento — revisitando bases teóricas, explorando nuances avançadas e analisando por que cada decisão arquitetural existe e como ela influencia na manutenção e evolução de sistemas.

Meu objetivo é criar um material organizado, prático e que sirva tanto para meu aprendizado contínuo quanto como referência para outras pessoas interessadas no tema.

🎯 Objetivo do Repositório

Aprimorar meu domínio sobre os princípios que sustentam a Clean Architecture.

Revisitar conceitos básicos e avançados, entendendo suas justificativas e impactos.

Explorar diferentes formas de aplicar Clean Architecture em projetos reais.

Criar exemplos, reflexões e anotações em branches específicas por tópico.

Consolidar boas práticas e padrões utilizados em ambientes profissionais.

📚 O que está sendo estudado

Cada tópico será explorado em uma branch dedicada, permitindo acompanhar a evolução e comparar diferentes abordagens.

🔹 Mas o que é Clean Architecture?

Uma arquitetura centrada no domínio, que organiza o código em camadas independentes, priorizando regras de negócio e mantendo detalhes de implementação — como frameworks, banco de dados e transportes — isolados e substituíveis.

🔹 Domain-Centric Architectures
Entendendo por que o domínio deve estar no centro das decisões e como isso traz manutenibilidade, flexibilidade e testabilidade.

🔹 Infraestrutura por Trás da Clean Architecture
Exploração da camada de infraestrutura, seus limites e como evitar que ela se torne acoplada ao domínio.

🔹 Diminuindo o Escopo: Domínio e Infraestrutura
Como simplificar a arquitetura sem perder seus princípios essenciais.

🔹 Aprofundando nas Camadas da Arquitetura
Uma análise detalhada das responsabilidades de cada camada e como elas se comunicam.

⚙️ Vantagens da Clean Architecture

- Baixo acoplamento

- Alta testabilidade

- Facilidade de manutenção e evolução

- Independência de frameworks

- Organização clara das responsabilidades

- Possibilidade de trocar banco, transportes, frameworks sem afetar a regra de negócio

⚠️ Desafios da Clean Architecture

- Curva de aprendizado inicial

- Aumento de boilerplate

- Implementações exageradas quando o escopo é pequeno

- Risco de superengenharia

- Necessidade de disciplina da equipe para manter os princípios

🗂️ Estrutura do Repositório

1. 00-introducao <br>
    ✔ O que é Clean Architecture <br>
    ✔ Objetivos do estudo <br>
    ✔ Visão geral das camadas <br>
    ✔ Relação com Domain-Driven Design <br>

2. 01-domain-centric-architectures <br>
    ✔ Estudo sobre arquiteturas centradas no domínio <br>
    ✔ Por que o domínio deve ser independente <br>
    ✔ Comparação com outras arquiteturas (Layered, Hexagonal, Onion) <br>

3. 02-entendendo-infraestrutura <br>
    ✔ Papel da infraestrutura <br>
    ✔ Como isolar detalhes externos <br>
    ✔ Riscos de acoplamento indevido <br>
    ✔ Exemplos simples de infraestrutura <br>

4. 03-escopo-clean-architecture <br>
    ✔ Reduzindo a arquitetura ao essencial (Domínio + Infra) <br>
    ✔ Quando simplificar <br>
    ✔ Trade-offs entre complexidade e necessidade <br>

5. 04-camadas-clean-architecture <br>
    ✔ Entities <br>
    ✔ Use Cases / Application <br>
    ✔ Interface Adapters <br>
    ✔ Infra <br>
    ✔ Como elas se comunicam <br>

6. 05-dependency-rule <br>
    ✔ Regra das dependências <br>
    ✔ Fluxo de dependências sempre para dentro <br>
    ✔ Como evitar violações <br>
    ✔ Exemplos de inversão <br>

7. 06-dependency-inversion-principle <br>
    ✔ DIP aplicado dentro da Clean Architecture <br>
    ✔ Interfaces no domínio <br>
    ✔ Implementações externas plugáveis <br>
    ✔ Benefícios e problemas comuns <br>

8. 07-explorando-vantagens <br>
    ✔ Testabilidade <br>
    ✔ Independência de frameworks <br>
    ✔ Baixo acoplamento <br>
    ✔ Substituição de tecnologias com baixo impacto <br>

9. 08-desafios-e-limitacoes <br>
    ✔ Boilerplate <br>
    ✔ Superengenharia <br>
    ✔ Curva de aprendizado <br>
    ✔ Manutenção da disciplina arquitetural <br>

10. 09-exemplos-praticos <br>
    ✔ Pequeños exemplos <br>
    ✔ Exemplo com fluxo completo (domain → use case → adapter → infra) <br>
    ✔ Testes unitários e mocks <br>
    ✔ Demonstração de troca de banco/framework sem alterar domínio <br>

11. 10-projeto-final-clean-architecture <br>
    ✔ Aplicação exemplo completa <br>
    ✔ Conclusões, aprendizados e boas práticas <br>
    ✔ Pontos de evolução futura no repositório <br>

🚀 Onde quero chegar

Com este estudo, pretendo:

Solidificar minha compreensão teórica e prática da Clean Architecture.

Melhorar minha capacidade de tomar decisões arquiteturais mais conscientes.

Criar exemplos reais que possam ser reutilizados em futuros projetos.

Contribuir para a comunidade compartilhando conhecimento de forma clara e organizada.