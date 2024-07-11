# Python IA Inteligencia artificial e previsoes
    Terceira aula da Jornada Python da Hashtag Programação

# Desafio
    Com base na análise de dados de clientes de um banco, criar um modelo de IA que consiga ler as informações de um cliente e definir o score de crédito dele entre Poor, Standard ou Good.

# Base de dados Clientes
    -id_cliente: int,
    -mes: int,
    -idade: float,
    -profissao: string,
    -salario_anual: float,
    -num_contas: float,
    -num_cartoes: float,
    -juros_emprestimo: float,
    -num_emprestimos: float,
    -dias_atraso: float,
    -num_pagamentos_atrasados: float,
    -num_verificacoes_credito: float,
    -mix_credito: string (Bom, Normal ou Ruim),
    -divida_total: float,
    -taxa_uso_credito: float,
    -idade_historico_credito: float,
    -investimento_mensal: float,
    -comportamento_pagamento: string (baixo_gasto_pagamento_alto, baixo_gasto_pagamento_medio, baixo_gasto_pagamento_baixo,  alto_gasto_pagamento_alto, alto_gasto_pagamento_medio, alto_gasto_pagamento_baixos),
    -saldo_final_mes: float,
    -score_credito: string (Poor, Standard, Good),
    -emprestimo_carro: int,
    -emprestimo_casa: int,
    -emprestimo_pessoal: int,
    -emprestimo_credito: int,
    -emprestimo_estudantil: int

# Bibliotecas utilizadas
    - Pandas
    - Scikit-learn

# Modelos utilizados
    - Random Forest
    - K-Nearest Neighbors

# Passos
- Passo 0: Entender o desafio
- Passo 1: Importar a base de dados
- Passo 2: Preparar a base de dados para a inteligência artificial
    - Verificar se a base de dados tem valores vazios
    - Verificar se a base de dados tem linhas duplicadas
    - Verificar se a base de dados possui os tipos corretos das colunas
    - Fazer o tratamento das colunas
        - Rotular as colunas de texto
        - Separar o target (y) e as colunas que serão utilizadas para a previsão (x)
        - Separar a base de dados entre treino e teste
- Passo 3: Criar um modelo de IA
    - Importar os modelos
    - Instanciar os modelos
    - Treinar os modelos
- Passo 4: Escolher o melhor modelo
    - Testar os modelos
    - Calcular as acurácias
- Passo 5: Usar o modelo para novas previsões
    - Utilizar o modelo com maior acurácia
    - Importar nova base de dados (novos clientes)
    - Ajustar as colunas em string da nova base de dados
    - Fazer as previsões
