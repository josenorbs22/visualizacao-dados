# Instalação

- Criar venv:
  `python -m venv vis_dados`
- Abrir venv:
  `.\vis_dados\Scripts\activate`
- Instalar bibliotecas:
  `pip install -r "requirements.txt"`
- Disponibilizar o kernel para ser utilizado no Visual Studio Code:
  `python -m ipykernel install --user --name=vis_dados --display-name "Python (vis_dados)"`
- Fechar o VSC se já estiver aberto e reabri-lo
- Abrir o arquivo .ipynb e, no canto superior direito clicar em "Select Kernel", depois em "Jupyter Notebook" e escolher a opção "Python (vis_dados)".