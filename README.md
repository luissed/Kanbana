# Kanbana <img src="https://github.com/luissed/Kanbana/blob/main/assets/images/banana.webp" alt="banana" width="50"/>

Kanbana é um aplicativo simples de gerenciamento de tarefas para desktop, desenvolvido em Python com o framework Flet e com o SQLite para armazanamento dos dados. Este projeto visa fornecer uma interface intuitiva para organizar e acompanhar tarefas, permitindo aos usuários visualizar e marcar tarefas como concluídas.

## Funcionalidades
- **Cadastro e Login de Usuários:** Os usuários podem criar contas e fazer login para acessar suas listas de tarefas.
- **Gerenciamento de Tarefas:** As tarefas podem ser adicionadas, movidas entre diferentes estados (A fazer, Em andamento, Concluídas) e excluídas. Além disso, pode-se atribuir uma data de entrega da tarefa, que faz com que o programe acuse como Atrasada se a data for ultrapassada.
- **Interface Responsiva:** O aplicativo é projetado para funcionar bem em dispositivos desktop.

## Tecnologias Utilizadas
- **Python:** Linguagem de programação principal.
- **Flet:** Framework Python para criar interfaces gráficas.
- **SQLite:** Banco de dados leve para armazenar informações de usuário e tarefas.
- **GitKraken:** Gerenciamento de commits no GitHub e controle de versão.

## Pré-requisitos
Antes de começar, certifique-se de ter instalado:
- Python 3.6 ou superior
- Pip (gerenciador de pacotes do Python)

## Como Compilar e Executar
### 1. Clone o repositório
Primeiro, clone o repositório para o seu ambiente local e navegue até o diretório do projeto:

```
git clone https://github.com/luissed/Kanbana.git
cd Kanbana
```

### 2. Instalar Dependências
Instale o Flet, a biblioteca necessária para executar a aplicação:

```
pip install flet
```

### 3. Executar a Aplicação
Para executar a aplicação, abra o arquivo main.py utilizando o Flet:

```
flet run .../src/main.py
```
### 4. Executar com o Executável
Você pode baixar o arquivo `Kanbanana.exe` e executá-lo diretamente em seu computador.

#### Aviso sobre Falsos Positivos de Vírus

Ao executar o `Kanbanana.exe`, você pode receber uma notificação de trojan. Não se preocupe, trata-se de um "falso positivo". Isso ocorre porque a biblioteca Python PyInstaller, frequentemente usada por desenvolvedores para criar arquivos executáveis a partir de scripts Python, é também usada por indivíduos mal-intencionados. Como resultado, alguns antivírus identificam qualquer arquivo gerado com PyInstaller como um possível trojan.

Para mais informações e esclarecimentos, acesse: [PyInstaller False Positive](https://discuss.python.org/t/pyinstaller-false-positive/43171).

## Funcionamento do Programa
1. Crie um usuário e senha clicando em Registrar.

2. Faça Login utilizando seu usuário e senha criado.

3. Adicione tarefas clicando em +.

4. Remova tarefas clicando na lixeira.

5. Altere o estado das tarefas utilizando as setas < e >, que indicam estado anterior e estado posterior, respectivamente.

6. Você também pode utilizar a caixinha de check para marcar uma tarefa como concluída.

7. As tarefas vão automaticamente para a coluna de Atrasadas, quando as mesmas ultrapassam a data determinada sem serem concluídas.

8. Altere para o modo escuro ou para o modo claro!

9. Vá em configurações e edite sua senha ou apague sua conta se quiser.

10. Aproveite!

# Contato
Dúvidas podem ser retiradas por meio dos e-mails:

andreffilho45@ufmg.br - André Ferreira Filho;

laradepaula@ufmg.br - Lara de Paula Santos;

luised@ufmg.br - Luis Eduardo Donizete;
