# Casos de Uso

## UC01 – Autenticar Usuário

**Atores**
- Atleta
- Professor
- Nutricionista
- Administrador

**Pré-condições**
- O usuário deve possuir cadastro no sistema.

### Fluxo Principal

1. O usuário acessa a tela de login.
2. Informa e-mail e senha.
3. O sistema valida as credenciais.
4. O sistema identifica o perfil do usuário.
5. O sistema redireciona para o painel correspondente.

### Fluxo Alternativo

- Credenciais inválidas.
- Conta bloqueada.

---

## UC02 – Gerenciar Atletas

**Ator**
- Professor

### Fluxo Principal

1. Acessa "Gerenciar Atletas".
2. Seleciona "Novo Atleta".
3. Preenche os dados.
4. O sistema valida as informações.
5. O atleta é cadastrado.

### Fluxo Alternativo

- Dados obrigatórios não preenchidos.
- E-mail já cadastrado.

---

## UC03 – Criar Treino

**Ator**
- Professor

### Fluxo Principal

1. Seleciona um atleta.
2. Cria um treino.
3. Define exercícios.
4. Salva.
5. O atleta recebe o treino.

### Fluxo Alternativo

- Atleta inexistente.

---

## UC04 – Registrar Avaliação Física

**Ator**
- Professor

### Fluxo Principal

1. Seleciona um atleta.
2. Informa os dados físicos.
3. O sistema registra a avaliação.
4. O histórico é atualizado.

### Fluxo Alternativo

- Dados inválidos.

---

## UC05 – Visualizar Desempenho

**Ator**
- Atleta

### Fluxo Principal

1. Acessa o painel.
2. Seleciona "Desempenho".
3. O sistema apresenta gráficos, metas e evolução.

### Fluxo Alternativo

- Não existem avaliações registradas.

---

## UC06 – Consultar Relatórios

**Ator**
- Nutricionista

### Fluxo Principal

1. Seleciona um atleta autorizado.
2. Visualiza os indicadores físicos.
3. Analisa os relatórios.

### Fluxo Alternativo

- Atleta não autorizou acesso.

---

## UC07 – Gerenciar Usuários

**Ator**
- Administrador

### Fluxo Principal

1. Acessa o painel administrativo.
2. Cadastra, altera ou remove usuários.
3. Define permissões.
4. O sistema salva as alterações.

### Fluxo Alternativo

- Usuário inexistente.
