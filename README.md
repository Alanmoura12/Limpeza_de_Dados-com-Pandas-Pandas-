# ETL de Dados Salariais com Pandas

realiza um processo de ETL (Extração, Transformação e Carga) em um dataset de salários da área de tecnologia.

## Etapas realizadas

1. **Extração** – Leitura do arquivo `dadosBrutos.csv` (133.349 registros)
2. **Limpeza** – Remoção de 10 registros com valores nulos na coluna `work_year`
3. **Transformação** – Conversão de colunas e valores:
   - `work_year` → `ano` (alterado para tipo inteiro)
   - `experience_level` → `nivel` (valores renomeados: SE=senior, MI=pleno, EN=junior, EX=executivo)
4. **Carga** – Exportação para `dadosLimpos.csv` (133.339 registros)
