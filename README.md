# Calculadora - PySide6

Esta é uma calculadora simples com interface gráfica construída em Python utilizando a biblioteca **PySide6**. Ela foi criada para demonstrar o uso de widgets básicos, estilos com `qdarkstyle` e algumas validações de entrada.

## Requisitos

- Python 3.
- [PySide6](https://pyside.org/)
- [qdarkstyle](https://github.com/ColinDuquesnoy/QDarkStyleSheet)

Você pode instalar as dependências executando:

```bash
pip install PySide6 qdarkstyle
```

## Como executar

1. Acesse a pasta do código fonte:

```bash
cd Codigo_Calculadora
```

2. Execute o arquivo `main.py`:

```bash
python main.py
```

A janela da calculadora será aberta com todas as operações básicas disponíveis.

## Executável para Windows

Para conveniência, o repositório também inclui o arquivo `calculadora.exe`, que foi gerado a partir do código e pode ser executado diretamente em ambientes Windows sem a necessidade de instalar o Python.

## Estrutura do projeto

```
Calculadora-Pyside6/
├── Codigo_Calculadora/   # Código fonte da aplicação
│   ├── main.py           # Ponto de entrada
│   ├── buttons.py        # Botões e grade de operações
│   ├── display.py        # Campo de exibição
│   ├── info.py           # Label de informações
│   ├── main_window.py    # Janela principal
│   ├── styles.py         # Estilos (qdarkstyle + QSS)
│   ├── utils.py          # Funções auxiliares
│   ├── variables.py      # Configurações e tamanhos
│   └── files/
│       └── icon.png      # Ícone da aplicação
└── calculadora.exe       # Executável para Windows
```

Sinta-se à vontade para clonar o projeto, estudar o código e realizar modificações.
