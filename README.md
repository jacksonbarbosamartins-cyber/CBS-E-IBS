
Folha & DRE v7.12 (atualizado)
-----------------------------

Arquivos incluídos:
- folha_v7_12_atualizado.py  -> Aplicação Streamlit atualizada (configurável).
- requirements.txt           -> Dependências sugeridas.
- README.md                  -> Este arquivo.

Como usar:
1. Instale dependências (recomendado criar um virtualenv):
   pip install -r requirements.txt
2. Inicie o app:
   streamlit run folha_v7_12_atualizado.py
3. Na barra lateral: ajuste as alíquotas de CBS/IBS e clique em 'Salvar alíquotas' para persistir em config.json.

Observações:
- CBS e IBS são simulativos aqui. Ajuste as alíquotas conforme sua necessidade.
- INSS e IRRF usam tabelas incorporadas no código. Verifique fontes oficiais quando necessário.
