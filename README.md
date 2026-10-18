# Controle de Níveis de Água 

Este projeto simula um sistema de monitoramento de um reservatório de água executado diretamente no terminal. O objetivo principal é exibir mensagens de alerta visualmente distintas utilizando cores, variando conforme o nível crítico ou seguro do reservatório.


## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Colorama** (Biblioteca para estilização e inserção de cores no terminal)

## Exemplo
![Exemplo do Controle de Nível de Água](https://github.com/josetorres37/controle-nivel-agua/blob/imagem/exemplo.png)

## 📋 Tabela de Níveis e Cores do Sistema

| Nível do Reservatório | Situação | Cor Utilizada |
| :---: | :--- | :--- |
| **Nível 1** | Muito baixo (crítico) | Vermelho |
| **Nível 2** | Baixo | Amarelo |
| **Nível 3** | Médio | Verde |
| **Nível 4** | Alto | Ciano |
| **Nível 5** | Muito alto (alerta) | Azul |

## 🚀 Como Executar o Projeto

### Pré-requisitos
Antes de iniciar, você precisa ter o **Python** instalado em sua máquina e a biblioteca **Colorama**.

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/josetorres37?tab=repositories
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd [controle-nível-agua]
   ```

3. **Instale a biblioteca Colorama:**
   ```bash
   pip install colorama
   ```

4. **Execute o arquivo principal:**
   ```bash
   python app.py
   ```

## 🧑‍💻 Autor
Desenvolvido por **[Jose Flavio Torres]**.
