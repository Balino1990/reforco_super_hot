# reforco_super_hot
Aplicação simples de folha de professor. 

Professor Finance App
Este é um sistema simples de acompanhamento de ganhos mensais para professores, desenvolvido em Python. A aplicação permite o cadastro de turmas, alunos, aulas extras, feriados, matérias, e a geração de um relatório financeiro mensal em formato JSON. Todos os dados podem ser facilmente configurados e armazenados em um único arquivo JSON.

Funcionalidades
Cadastro e Configuração de Turmas: Criação de turmas de diferentes tipos (Aulas de Curso, Workshops, Super Módulo), com opções de valor e quantidade de aulas.
Aulas Extras: Registro de aulas extras (Reposição, Reforço) com valores associados.
Cadastro de Feriados: Adição de feriados para registrar dias em que as aulas não ocorrerão.
Gestão de Alunos: Cadastro de alunos com possibilidade de inscrição em múltiplas turmas e controle de frequência e valores pagos.
Descontos e Isenções: Configuração de descontos e isenções aplicáveis a turmas ou alunos, por percentual ou valor fixo.
Cadastro de Matérias: Listagem de matérias com número de aulas.
Relatório de Ganhos Mensais: Geração de um relatório financeiro mensal com resumo dos ganhos totais e detalhes de turmas e alunos.
Estrutura de Arquivos
plaintext
Copiar código
professor-finance-app/
├── professor_finance_app.py       # Arquivo principal da aplicação
├── dados_financeiros.json         # Arquivo JSON gerado com os dados financeiros
└── README.md                      # Este arquivo README
Como Usar
Clone o repositório para seu computador.

Abra o terminal na pasta raiz do projeto.

Instale o Python (versão 3.6 ou superior, caso ainda não tenha).

Execute o arquivo principal para gerar o arquivo JSON com os dados configurados:

bash
Copiar código
python professor_finance_app.py
Esse comando irá gerar um arquivo chamado dados_financeiros.json com todas as informações de turmas, alunos, feriados e o relatório financeiro do mês.

Configuração e Personalização
Para adicionar dados como turmas, aulas extras, feriados, alunos e matérias, edite o arquivo professor_finance_app.py nas seções correspondentes. Os dados são estruturados em classes, e cada entidade possui métodos para configuração e adição de dados.

Estrutura do Arquivo JSON
O arquivo dados_financeiros.json terá a seguinte estrutura:

json
Copiar código
{
  "turmas": [...],
  "aulas_extras": [...],
  "feriados": [...],
  "alunos": [...],
  "descontos_e_isencoes": [...],
  "materias": [...],
  "relatorio_mensal": {...}
}
Exemplo de Uso
Para entender melhor como adicionar dados ao sistema, veja o exemplo fornecido no final do arquivo professor_finance_app.py. O exemplo inclui um caso básico de criação de turmas, alunos, feriados, entre outros, e a geração do relatório mensal.

Este código foi feito com auxilio do CHATGPT em uma sala de aula da escola Infinity School ministrada pelo professor Luan 
