# Politica-Info-Backend

## Desenvolvedores - Alunos

- Antonio Araujo Pavão, antonio.pavao@aluno.faculdadeimpacta.com.br, 1904632, 5A
- Caroline Araujo de Souza, caroline.asouza@aluno.faculdadeimpacta.com.br, 1905063, 5B
- Giovana Victória da Silva Mendes, giovana.mendes@aluno.faculdadeimpacta.com.br, 1902710, 5A
- Leandro de Azevedo Souza, leandro.azevedo@aluno.faculdadeimpacta.com.br, 1904574, 5A
- Matheus Chiarello, matheus.chiarello@aluno.faculdadeimpacta.com.br, 1905369, 5A

## Descrição Técnica

O projeto será uma apresentação dos dados relacionados à política, mas precisamente de Deputados, tais como quantidade de deputados ativos, seus partidos e os estados que se referem, entre outros. Utilizaremos uma API disponibilizada no site da câmara dos deputados para consumo dessas informações. 

Abaixo, apresentamos algumas informações técnicas sobre o projeto:

### Linguagens
- Python (Front)
- HTML/CSS/Javascript (Back)
- SQL (Banco de Dados)

### Frameworks
- Bootstrap (Front)

### Plataformas
- SQL Server (Banco de Dados)
- Trello (Gerenciamento de Projeto)
- Github (Versionamento)
- VS Code (Editor de Código)

### APIs
- API Dados Abertos da Câmara dos Deputados - https://dadosabertos.camara.leg.br/swagger/api.html

### Endpoints utilizados
- Blocos (ambos)
- Deputados (;deptados, /id/deputados, /id/despesas)
- Partidos (/partidos, /partidos/{id})
- Referencias (UF, tipoDespesa)
- Votações (*)
- Orgaos (votacoes, membros)

## Lista de Requisitos

R01 - O Sistema DEVE receber dados sobre Deputados de modo automático (API)
R02 - O Sistema DEVE apresentar dados e indicadores sobre deputados
R03 - O Sistema DEVE apresentar dados e indicadores sobre partidos
R04 - O Sistema DEVE apresentar dados e indicadores sobre orgãos governamentais
R05 - O Sistema DEVE ser acessar via web sem a necessidade de um cadastro de usuário inicial
R06 - O Sistema DEVE conter opções de filtros para utilização na visualização dos dados apresentados
R07 - O Sistema DEVE permitir o cadastro de usuário com Nome, Email e Senha, bem como sua exclusão, edição e consulta
R08 - O Sistema NÃO DEVE permitir a inclusão de um usuário com email já cadastrado
R09 - O Sistema DEVE conter uma página de login e senha

### Requisito Prioritário AC1
R01 - O Sistema DEVE receber dados sobre Deputados de modo automático (API)

### Requisito Prioritário AC2
R09 - O Sistema DEVE conter uma página de login e senha




