# Trabalho de Programação — UNINTER

Repositório destinado à atividade prática realizada para a disciplina de Programação III, desenvolvida durante minha graduação em Engenharia de Software na **UNINTER**.

Os projetos deste repositório foram desenvolvidos em **Python**, com foco no aprendizado e na aplicação de conceitos de **estruturas de dados**, especialmente listas encadeadas e tabelas hash.

## 📚 Trabalhos

### 1. Cadastro de Pacientes

**Arquivo:** `cadastro_pacientes.py`

Implementação de uma fila de atendimento hospitalar utilizando **lista encadeada simples**.

O programa permite:

- Cadastrar pacientes;
- Gerar cartões verdes e amarelos com numeração automática;
- Dar prioridade aos pacientes com cartão amarelo;
- Manter a ordem crescente dos cartões dentro de cada categoria;
- Visualizar a lista de pacientes aguardando atendimento;
- Chamar o próximo paciente da fila.

**Estrutura principal:**

- `CartaoPaciente` — representa o nodo da lista encadeada;
- `FilaPacientes` — controla a fila e as operações de inserção e atendimento.

---

### 2. Registro de Estados

**Arquivo:** `registro_estados.py`

Implementação de uma **tabela hash com tratamento de colisões por encadeamento**, utilizando listas encadeadas.

O programa trabalha com as siglas dos **26 estados brasileiros e do Distrito Federal**, armazenando os registros nas posições da tabela de acordo com uma função hash.

O programa permite:

- Criar uma tabela hash com 10 posições;
- Inserir os estados brasileiros;
- Utilizar listas encadeadas para tratar colisões;
- Aplicar uma função hash baseada nos valores ASCII das siglas;
- Tratar o Distrito Federal de acordo com a regra específica da atividade;
- Visualizar o conteúdo da tabela hash;
- Inserir um registro fictício para testar a tabela.

**Estrutura principal:**

- `Estado` — representa o nodo da lista encadeada;
- `ListaEncadeada` — controla os estados armazenados em cada posição;
- `TabelaHash` — controla a tabela e realiza o cálculo da posição através da função hash.

---

## 🛠️ Tecnologias utilizadas

- **Python 3**
- **Listas Encadeadas**
- **Tabela Hash**
- **Estruturas de Dados**

## 🎓 Instituição

**UNINTER — Centro Universitário Internacional**

Repositório criado para fins acadêmicos e para registro dos trabalhos desenvolvidos durante a graduação de Engenharia de Software.

---

## 👨‍💻 Autor

**Dener Xisto da Fonseca**
