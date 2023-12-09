# analise-renda-variaveis-qualitativas
# Análise de Variáveis Qualitativas e Renda

## Introdução
Este projeto tem como objetivo analisar se as variáveis qualitativas "posse de imóvel" e "posse de veículo" podem ser consideradas boas preditoras da variável quantitativa "renda". Utilizei técnicas estatísticas e visualizações de dados para explorar essas relações.

## Passos Realizados

1. **Carregamento dos Dados:**
   - Utilizei o Pandas para carregar o conjunto de dados "previsao_de_renda.csv".

2. **Limpeza de Dados:**
   - Verifiquei e corrigi valores faltantes nas colunas numéricas preenchendo-os com a média.

3. **Visualização de Dados:**
   - Converti os valores booleanos de "posse_de_imovel" e "posse_de_veiculo" em rótulos categóricos.
   - Criei gráficos de barras usando Seaborn para avaliar a distribuição das variáveis qualitativas no tempo.

4. **Análise Descritiva:**
   - Realizei uma análise descritiva das variáveis qualitativas ao longo do tempo, destacando insights relevantes.

5. **Médias ao Longo do Tempo:**
   - Construí gráficos de barras mostrando as médias de cada nível das variáveis qualitativas no tempo.
   - Avaliei a estabilidade e a possibilidade de utilização dessas variáveis em modelagem.

## Resultados e Conclusões

### Distribuição das Variáveis Qualitativas ao Longo do Tempo

#### 1. Distribuição por Sexo:
   - O número de registros para ambos os sexos é bastante equilibrado.
   - Não parece haver uma mudança significativa na distribuição ao longo do tempo.

#### 2. Distribuição por Posse de Veículo:
   - A maioria dos registros indica posse de veículo.
   - A distribuição parece relativamente constante ao longo do tempo.

#### 3. Distribuição por Posse de Imóvel:
   - A maioria dos registros possui imóvel.
   - A distribuição mantém-se estável ao longo do tempo.

#### 4. Distribuição por Tipo de Renda:
   - A categoria "Assalariado" é a mais frequente, seguida por "Empresário" e "Bolsista".
   - Pode haver uma pequena flutuação na distribuição ao longo do tempo, mas não é dramaticamente diferente.

#### 5. Distribuição por Nível de Educação:
   - A maioria dos registros tem nível de educação "Secundário".
   - As categorias "Pós graduação" e "Primário" têm menos representação.
   - A distribuição parece relativamente constante ao longo do tempo.

#### 6. Distribuição por Estado Civil:
   - A maioria dos registros é de pessoas "Casadas" ou "Solteiras".
   - As outras categorias de estado civil têm menor representação.
   - A distribuição parece razoavelmente constante.

### Médias das Variáveis Qualitativas ao Longo do Tempo

#### Sobre Alterações Significativas:
   - Não parece ter ocorrido mudanças importantes nas variáveis qualitativas ao longo do tempo. Elas mantiveram padrões consistentes, sugerindo estabilidade. Isso é positivo ao considerar a utilização dessas variáveis em modelos preditivos.

#### Sobre a Utilização em Modelagem:
   - As variáveis qualitativas (como sexo, posse de veículo, posse de imóvel, tipo de renda, nível de educação e estado civil) parecem estáveis ao longo do tempo, o que é bom para usar em modelos. A estabilidade sugere que elas mantiveram padrões consistentes. No entanto, a decisão final depende dos objetivos específicos do modelo e de análises mais detalhadas.

## Como Executar o Código
1. Certifique-se de ter o Python e as bibliotecas necessárias instaladas (pandas, seaborn, matplotlib, scipy).
2. Baixe o arquivo "previsao_de_renda.csv".
3. Execute o código Python, ajustando o caminho do arquivo conforme necessário.

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---
