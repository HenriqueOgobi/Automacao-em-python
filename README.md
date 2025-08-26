# 📊 Automação de Relatórios de Compras com Python  

Este projeto foi desenvolvido como um desafio para automatizar tarefas repetitivas de um analista:  
enviar diariamente um relatório de compras para o gestor da empresa.  

A automação foi feita em **Python** utilizando bibliotecas de automação de processos e manipulação de dados.  

---

## 🚀 O que o projeto faz  
- Abre automaticamente o sistema da empresa via navegador.  
- Realiza login com usuário e senha.  
- Exporta a base de dados de compras.  
- Processa os dados com **pandas**, calculando:  
  - ✅ Total gasto  
  - ✅ Quantidade de produtos comprados  
  - ✅ Preço médio dos produtos  
- Envia um e-mail para o gestor com o relatório pronto.  

---

## 🛠️ Tecnologias utilizadas  
- [Python 3](https://www.python.org/)  
- [PyAutoGUI](https://pyautogui.readthedocs.io/) → Automação do mouse e teclado  
- [Pandas](https://pandas.pydata.org/) → Manipulação e análise de dados  
- [Pyperclip](https://pypi.org/project/pyperclip/) → Copiar/colar texto  

---

## 📂 Estrutura atual do repositório
📦 automacao-relatorio-compras
┣ 📂 .ipynb_checkpoints
┣ 📜 Projeto1 - Arquivo Inicial.ipynb
┗ 📜 README.md

## 📧 Exemplo do relatório enviado por e-mail
Prezados,
Segue o relatório de compras:

Total gasto: R$ 7.254.196,58
Quantidade de produtos: 9.715
Preço médio: R$ 746,70

Qualquer dúvida, estou à disposição.
Att,
Henrique Oliveira Gobi

## ▶️ Como executar
1. Clone este repositório  
   ```bash
   git clone https://github.com/seuusuario/automacao-relatorios-python.git
Instale as dependências necessárias

pip install pandas pyautogui pyperclip
Abra o notebook no Jupyter ou Google Colab e execute as células.

💡 Observações
Este projeto é apenas um exercício prático para demonstrar o uso de Python em automação.

Alguns trechos do código usam coordenadas do mouse (x, y) que podem variar de máquina para máquina.

✍️ Desenvolvido por Henrique Oliveira Gobi
