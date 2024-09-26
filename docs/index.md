<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

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
* Aluno 2: Renan Garrido - 10417093
* Aluno 3: Rodrigo Roveratti Guerrero - 10417090
* Aluno 4: Otto Martins Mota - 10418170



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

#### 1. **Efetuar Login**
   - **Atores**: Professor, Aluno, Pais
   - **Descrição**: O usuário acessa a plataforma web ou mobile e realiza o login com suas credenciais (e-mail e senha).
   - **Pré-condição**: O usuário deve estar previamente cadastrado.
   - **Fluxo principal**:
     1. O usuário acessa a tela de login.
     2. Insere e-mail e senha.
     3. O sistema valida as credenciais.
     4. Caso válido, o usuário é redirecionado à sua área.
   - **Fluxo alternativo**:
     - Caso as credenciais sejam inválidas, o sistema exibe uma mensagem de erro.
     - Caso o usuário esqueça a senha, pode acessar a opção "Esqueci a senha" para redefinição.
   - **Requisitos Não-Funcionais**: O login deve ocorrer em até 2 segundos.

#### 2. **Alterar Senha**
   - **Atores**: Professor, Aluno, Pais
   - **Descrição**: Permitir que o usuário altere sua senha de acesso na plataforma.
   - **Pré-condição**: O usuário deve estar autenticado.
   - **Fluxo principal**:
     1. O usuário acessa a opção "Configurações" e seleciona "Alterar Senha".
     2. Insere a senha atual e a nova senha.
     3. O sistema valida a senha atual e confirma a alteração.
   - **Requisitos Não-Funcionais**: Garantir que as senhas sejam criptografadas no banco de dados.

#### 3. **Criar Turma**
   - **Atores**: Professor, Administrador
   - **Descrição**: Permite ao professor ou administrador criar e configurar uma nova turma.
   - **Pré-condição**: O usuário deve possuir permissões de professor ou administrador.
   - **Fluxo principal**:
     1. O professor/administrador acessa a opção "Criar Turma".
     2. Insere os dados da turma (nome, ano, disciplinas associadas).
     3. O sistema registra a turma e a disponibiliza para o controle de presença.
   - **Requisitos Funcionais**: Associa matérias e professores à turma.

#### 4. **Matricular Aluno**
   - **Atores**: Professor, Administrador
   - **Descrição**: Permite ao professor ou administrador matricular alunos em uma turma.
   - **Pré-condição**: A turma deve estar previamente criada.
   - **Fluxo principal**:
     1. O usuário acessa a turma e seleciona a opção "Matricular Aluno".
     2. Insere o nome do aluno e as informações de contato dos pais (e-mail).
     3. O sistema registra o aluno na turma e associa os pais.
   - **Requisitos Não-Funcionais**: Garantir o cadastro correto e a segurança dos dados dos alunos e pais.

#### 5. **Registrar e Lançar Faltas**
   - **Atores**: Professor
   - **Descrição**: O professor registra a presença e as faltas dos alunos para cada aula.
   - **Pré-condição**: A turma e a aula devem estar previamente configuradas.
   - **Fluxo principal**:
     1. O professor acessa a turma e seleciona a aula atual.
     2. Marca os alunos presentes e ausentes.
     3. O sistema atualiza o histórico de frequência dos alunos.
   - **Fluxo alternativo**: Em caso de erro no lançamento, o professor pode editar os dados posteriormente.
   - **Requisitos Funcionais**: A presença deve ser registrada de maneira simples e eficiente.

#### 6. **Consultar Faltas**
   - **Atores**: Aluno, Pais
   - **Descrição**: Permite que os alunos e pais consultem o histórico de faltas.
   - **Pré-condição**: O aluno deve estar matriculado e ter frequência registrada.
   - **Fluxo principal**:
     1. O aluno ou pai acessa a plataforma e seleciona a opção "Consultar Faltas".
     2. O sistema exibe o histórico de frequência do aluno, por matéria.
   - **Requisitos Funcionais**: O histórico deve ser exibido de forma clara, com as porcentagens de presença.

#### 7. **Gerar E-mail Caso Exceda 20% de Faltas**
   - **Atores**: Sistema (automático)
   - **Descrição**: O sistema gera uma notificação automática para os pais se a presença do aluno for inferior a 80% em alguma matéria.
   - **Pré-condição**: O aluno deve ter mais de 20% de faltas.
   - **Fluxo principal**:
     1. O sistema verifica a frequência do aluno periodicamente.
     2. Se as faltas excederem 20%, uma notificação por e-mail é enviada aos pais.
   - **Requisitos Não-Funcionais**: Garantir que o e-mail seja enviado em até 24 horas após a ocorrência da falta.

#### 8. **Reprovar Caso Exceda 25% de Faltas**
   - **Atores**: Sistema (automático)
   - **Descrição**: O sistema reprova automaticamente um aluno se ele tiver mais de 25% de faltas.
   - **Pré-condição**: O aluno deve ter mais de 25% de faltas.
   - **Fluxo principal**:
     1. O sistema verifica a frequência do aluno periodicamente.
     2. Se as faltas excederem 25%, o aluno é reprovado e a informação é registrada no sistema.
   - **Requisitos Funcionais**: Garantir que a reprovação seja automática, com notificação ao professor.

#### 9. **Gerar Log de Acesso**
   - **Atores**: Sistema (automático)
   - **Descrição**: O sistema gera logs de acesso de professores, alunos e pais, para fins de auditoria.
   - **Pré-condição**: O usuário deve realizar ações dentro do sistema.
   - **Fluxo principal**:
     1. A cada login ou ação importante, o sistema registra o evento no log de acesso.
     2. O administrador pode consultar os logs quando necessário.
   - **Requisitos Não-Funcionais**: Garantir que os logs sejam armazenados de forma segura e acessível somente a administradores.


# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
