# Planejamento de desenvolvimento, Biblioteca Digital

## What: 
   Este documento apresenta o planejamento para o desenvolvimento do software denominado Biblioteca Digital, que consiste em uma aplicação web voltada à disponibilização, organização e consulta de conteúdos literários digitais, como livros, HQs e mangás, permitindo aos usuários navegar pelo acervo, consultar autores, realizar autenticação e contribuir com novos conteúdos.

## Why: 
   A Biblioteca Digital surge como uma solução para centralizar conteúdos literários em um único ambiente online, facilitando o acesso à informação de forma prática e intuitiva. Por meio da aplicação web, os usuários podem consultar obras de diferentes categorias a qualquer momento, sem restrições de local ou dispositivo.

# Who: 
### Equipe: 
    * PO 
    * Desenvolvedor Pleno Full Stack
    * DevOps 
    * QA 

### Responsabilidades: 

#### PO (Product Owner) 
   Responsável por definir os requisitos do sistema, priorizar funcionalidades, manter a visão do produto e garantir que o desenvolvimento atenda aos objetivos da Biblioteca Digital.
   
#### Desenvolvedor Full Stack
   Responsável pela implementação das funcionalidades do frontend e backend, integração com o banco de dados, versionamento do código e manutenção da aplicação.

#### DevOps 
   Será responsável por construir toda a infraestrutura do sistema e fazer o deploy das versões beta semanalmente. 

#### QA 
   Responsável por validar a qualidade do sistema, realizando testes funcionais e não funcionais, garantindo que as funcionalidades estejam de acordo com os requisitos definidos.

## When: 
   Este planejamento visa a entrega da versão 1.0 da Biblioteca Digital até o final do semestre letivo. O desenvolvimento será realizado de forma incremental, seguindo o cronograma abaixo.

### Cronograma de Desenvolvimento 

| Data de Início | Mile Stone | QA | Deploy | Dificuldade Fibonacci (Referente ao desenvolvimento)| Data Final |
| :--- | :---: | :---: | :---: | :---: | ---: |
| 15/12/2025 | Estrutura inicial e página Home | - | - | 13 | 20/12/2025 |
| 22/12/2025 | Autenticação (Login e Registro) e página Sobre | Home | - | 21 | 27/12/2025 |
| 29/12/2025 | página Acervo, página Livros e Autores | Autenticação | Home | 34 | 03/01/2026 |
| 05/01/2026 | página HQs, página Mangás e Navegação Geral | Acervo | Autenticação | 21 | 10/01/2026 |
| 12/01/2026 | página Contribuição e Rodapé | Navegação | Acervo | 13 | 17/01/2026 |
| 19/01/2026 | Correção de Bugs e Ajustes | Revisão geral | - | - | 24/01/2026 |

Ao final deste cronograma, a aplicação contará com todas as funcionalidades descritas no repositório do projeto.

## Where: 
   Todo o desenvolvimento será realizado em regime home-office, com organização centralizada no GitHub, que será utilizado para versionamento de código, documentação e controle de tarefas. As reuniões de alinhamento poderão ocorrer de forma remota, utilizando ferramentas de videoconferência.

## How  
   O desenvolvimento da Biblioteca Digital seguirá práticas ágeis, utilizando o framework Scrum, com ciclos curtos de desenvolvimento (sprints).

### Metodologia de Desenvolvimento  
Serão adotadas as seguintes práticas:
1. planejamento de tarefas por sprint
2. revisões periódicas do progresso
3. testes contínuos
4. controle de versão com Git
5. As tarefas serão organizadas no GitHub Projects, permitindo visualização de progresso. Serão definidos critérios de aceitação claros para cada tarefa, e métricas de qualidade do código serão monitoradas, incluindo cobertura mínima de testes e aprovação obrigatória em code review.   

### Processo de Desenvolvimento  
O fluxo de trabalho seguirá as seguintes etapas:  

1. Definição da tarefa (PO)
2. Criação de branch no padrão:
feature/nome-da-funcionalidade
3. Desenvolvimento da funcionalidade
4. Commits organizados e versionamento
5. Revisão do código 
6. Testes funcionais
7. Merge na branch principal
8. Deploy da versão atualizada 

### Infraestrutura e Deploy   
* Aplicação hospedada em ambiente web
* Banco de dados para armazenamento de usuários e acervo
* Deploy contínuo utilizando GitHub
* Backups periódicos do banco de dados

### Segurança e Autenticação  
1. Autenticação de usuários via login e senha
2. Armazenamento seguro de credenciais (hashing)
3. Validação de dados enviados pelo usuário
4. Proteção contra acessos não autorizados

### Design e Experiência do Usuário  
* Interface simples e intuitiva  
* Layout consistente entre páginas
* Design responsivo para diferentes dispositivos
* Organização clara das informações do acervo 

### Documentação  
1. Documentação técnica em Markdown no repositório
2. Diagramas UML (caso de uso e sequência)
3. README com instruções de uso e navegação
4. Registro de decisões técnicas do projeto

### Manutenção Pós-Lançamento  
#### Após o lançamento da versão 1.0, serão realizadas:
* Correções de bugs
* Melhorias de usabilidade
* Inclusão de novas funcionalidades conforme feedback dos usuários 

## How much 

O desenvolvimento do website Biblioteca Virtual, destinado ao acesso e organização de conteúdos literários digitais, envolve custos estimados relacionados à alocação da equipe de desenvolvimento, ferramentas utilizadas, infraestrutura tecnológica, publicação e manutenção pós-lançamento.

### Custos da Equipe: 

| Profissional | Quantidade | Regime | Total mensal (R$) |
| :----------: | :--------: | :----: | :---------------: |
| Product Owner | 1 | Full time | 7.500 |
| Dev Pleno Full Stack | 1 | Full time | 10.000 | 
| DevOps | 1 | Meio período | 4.500 |
| QA | 1 | Full time | 6.000 |

Subtotal mensal da equipe: R$ 28.000,00

### Custos com ferramentas de design, documentação e gerenciamento: 

| Ferramenta | Custo (R$) | Observação |
| :--------: | :--------: | :--------: |
| Figma | 00.0 | Plano gratuito atende |
| Github | 00.0 |Totalmente gratuito |
| VS Code | 00.0 |Open Source |
| Ferramentas de diagramação | 00.0 | Gratuito |

Subtotal ferramentas: R$ 0,00 

### Referência de mercado para infraestrutura técnica: 

O backend do SiMa, o banco de dados e os pipelines de integração contínua já são fornecidos pelo Centro Paula Souza. Para fins de planejamento orçamentário e referência técnica, apresentamos uma estimativa de mercado: 

| Recurso Técnico | Estimativa Mensal em Reais (R$) | Observação |
| :--------: | :--------: | :--------: |
| Servidor Web / Backend | 150 a 300 | Hospedagem da aplicação |
| Banco de Dados | 50 a 100 | Armazenamento do acervo |
| Monitoramento e Logs | 30 a 60 | Observabilidade do sistema |
| Certificado SSL | 0,00 | Incluso em serviços cloud |
| CI/CD (GitHub Actions) | 0,00 | Plano gratuito da plataforma |

Estimativa mensal de infraestrutura: R$ 230 a R$ 460

### Custo estimado do projeto: 
* Equipe: R$ 84.000,00
* Infraestrutura: R$ 690 a 1.380 
* Ferramentas: R$ 0,00 
* Reserva de risco (15%): R$ 12.600,00

É considerada uma reserva de 15% sobre o custo da equipe, conforme boas práticas de gestão de projetos (PMBOK), destinada a cobrir riscos e ajustes não previstos.

Total estimado: aproximadamente R$ 97.290,00 a R$ 97.980,00 

