<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Ciência da Computação</a></h3>


<font size="+12"><center>
*&lt;Sistema de Controle de Faltas para Escolas&gt;*
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Aluno 1: Gustavo Fugulin Soares da Silva
* Aluno 2: Otto Martins Mota - 10418170
* Aluno 3: Renan Garrido - 10417093
* Aluno 4: Rodrigo Roveratti Guerrero - 10417090



# Descrição do Projeto
O projeto trata-se de uma plataforma híbrida web/mobile, em que, o principal objetivo é fazer o controle de presença dos aulos de 1ª à 5ª série. Inicialmente, o sistema será subdivido em turmas para facilitar a organização, devido ser um professor para diversas matérias e alguns porfessores para as matérias de Educação Física e Inglês. O sistema fará o controle das faltas, gerárá relatórios e, caso, o aluno esteja com menos de 80% de presença em alguma(s) matérias o sistemas enviará notificações aos pais através do e-mail.
*&lt;Introdução do projeto&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais
### Requisitos Funcionais
1. **Gerenciamento de Usuários**
   - **Cadastro e Login**: Permitir que professores, alunos e pais se cadastrem e façam login na plataforma.
   - **Perfis de Usuário**: Permitir a criação e edição de perfis para professores, alunos e pais, com informações como nome, e-mail e senha.
   - **Atribuição de Papéis**: Permitir a atribuição de diferentes papéis (professor, aluno, pai) e permissões associadas.

2. **Gerenciamento de Turmas e Matérias**
   - **Criação de Turmas**: Permitir que professores e administradores criem e gerenciem turmas.
   - **Atribuição de Matérias**: Associar matérias a turmas e atribuir professores a essas matérias.
   - **Registro de Aulas**: Registrar detalhes das aulas, incluindo data, hora e matérias abordadas.

3. **Controle de Presença**
   - **Registro de Presença**: Permitir que professores registrem a presença ou falta dos alunos para cada aula.
   - **Visualização de Presença**: Permitir que alunos e pais visualizem o histórico de presença.

4. **Relatórios de Presença**
   - **Geração de Relatórios**: Gerar relatórios de presença para turmas, matérias e alunos, incluindo estatísticas e gráficos.
   - **Exportação de Relatórios**: Permitir a exportação de relatórios em formatos como PDF e Excel.

5. **Notificações e Alertas**
   - **Notificação de Falta**: Enviar notificações automáticas aos pais via e-mail quando um aluno tiver menos de 80% de presença em uma matéria.
   - **Alertas de Ausência**: Notificar os pais sobre faltas recentes ou problemas com a frequência.

6. **Interface e Navegação**
   - **Interface Web e Mobile**: Desenvolver interfaces responsivas e intuitivas para plataformas web e mobile.
   - **Acessibilidade**: Garantir que a plataforma seja acessível a usuários com deficiência.

7. **Segurança**
   - **Autenticação e Autorização**: Implementar autenticação segura e controle de acesso baseado em papéis.
   - **Criptografia**: Utilizar criptografia para proteger dados sensíveis, como informações pessoais e relatórios.

### Requisitos Não-Funcionais

1. **Desempenho e Escalabilidade**
   - **Tempo de Resposta**: O sistema deve responder a ações dos usuários, como registro de presença e geração de relatórios, em menos de 2 segundos.
   - **Escalabilidade**: O sistema deve ser capaz de suportar um número crescente de usuários e turmas sem degradação significativa de desempenho.

2. **Usabilidade**
   - **Interface Intuitiva**: A interface deve ser fácil de usar e entender, com uma navegação clara e um design responsivo para diferentes dispositivos.
   - **Treinamento e Suporte**: Fornecer materiais de treinamento e suporte para usuários que precisem de ajuda com a plataforma.

3. **Segurança**
   - **Proteção de Dados**: Implementar medidas para proteger dados sensíveis contra acesso não autorizado e ataques cibernéticos.
   - **Backup e Recuperação**: Realizar backups regulares dos dados e garantir que existam processos para recuperação em caso de falha.

4. **Manutenibilidade e Extensibilidade**
   - **Código Limpo**: Manter o código organizado e documentado para facilitar a manutenção e a adição de novas funcionalidades.
   - **Arquitetura Modular**: Utilizar uma arquitetura modular para permitir a fácil adição de novos recursos e a modificação de funcionalidades existentes.

5. **Compatibilidade**
   - **Browsers e Dispositivos**: Garantir que a plataforma seja compatível com os principais navegadores web (Chrome, Firefox, Safari) e sistemas operacionais móveis (iOS, Android).
   - **Integração com Outros Sistemas**: Se aplicável, permitir a integração com outros sistemas educacionais ou de gestão escolar.

6. **Conformidade**
   - **Regulamentações e Normas**: Garantir que o sistema esteja em conformidade com regulamentações de proteção de dados, como o GDPR ou a Lei Geral de Proteção de Dados (LGPD), e com normas educacionais relevantes.

# Diagrama de Atividades

![Diagrama de Atividae drawio](https://github.com/user-attachments/assets/e73af506-0586-4d25-8374-4b12c1bbc11d)

# Diagrama de Casos de Uso
![Novo Projeto](https://github.com/user-attachments/assets/14f37494-84c9-490a-8cc8-9e8da5edc454)



# Descrição dos Casos de Uso

![Diagrama de Requisitos drawio](https://github.com/user-attachments/assets/7c1c8f3f-2bcb-410e-8937-e8ce3d41414e)


[Descrição dos Casos de Uso Table.pdf](https://github.com/user-attachments/files/17149018/Descricao.dos.Casos.de.Uso.Table.pdf)


# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*
![image](https://github.com/user-attachments/assets/a8290d8d-029f-4a37-bf99-b3e786f1dca7)
![image](https://github.com/user-attachments/assets/8ef2d9af-1ef9-4806-a7fe-abbd5910e7a9)


# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*
![Classe UML](https://github.com/user-attachments/assets/9a7e1915-d6f0-4996-94ba-e3c3b5b31e39)



# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*
![Diagrama em branco](https://github.com/user-attachments/assets/dca5afaf-69cc-4b0e-8752-6cdf97d4cb6e)


# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*
![Diagrama de Implantação2](https://github.com/user-attachments/assets/80c63afa-cc7e-44b4-bf22-ca47049c1701)



# Referências

*&lt;Lista de referências&gt;*

Filho, W.D.P. P. (2019). Engenharia de Software – Produtos – Vol.1 (4th ed.).

Pressman, R. S., & Maxim, B. R. (2021). Engenharia de software (9th ed.). 

