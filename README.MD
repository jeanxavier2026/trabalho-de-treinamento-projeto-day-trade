# Sistema de Monitorização de Day Trade

Este projeto consiste num sistema prático desenvolvido para registar, organizar e analisar operações diárias nos mercados financeiros de ações e criptomoedas. A aplicação auxilia o investidor a gerir o seu risco diário, calculando automaticamente os lucros e as perdas de cada operação efetuada. Através desta ferramenta, é possível evitar erros emocionais e manter um histórico detalhado e consistente de toda a atividade de negociação.

![Logótipo do Projeto](https://unsplash.com)

##  Tecnologias Utilizadas

Esta tabela detalha os programas e tecnologias fundamentais que foram configurados e instalados no computador para colocar a aplicação a funcionar corretamente:

| Nome do Programa | Para que serve | Versão |
| :--- | :---: | ---: |
| MySQL | Armazena o histórico das operações | 8.0 |
| XAMPP | Executa o servidor local do sistema | 8.2 |
| VS Code | Ambiente de desenvolvimento do código | 1.85 |

>  **Aviso Importante:** Certifique-se de ativar os módulos Apache e MySQL no painel de controlo do XAMPP antes de iniciar qualquer registo na plataforma.

##  Instalação e Configuração

Siga estes três passos sequenciais simples para descarregar e testar o projeto no seu ambiente local:

1. Descarregue os ficheiros do repositório para o seu computador.
2. Abra a pasta raiz do projeto utilizando o seu editor de texto preferido.
3. Execute o arquivo de comandos para estruturar a base de dados inicial.

### Configurações Iniciais

As credenciais padrão de acesso à base de dados encontram-se estruturadas dentro do ficheiro `config.txt` na pasta principal. Para criar o seu espaço de trabalho no banco de dados e preparar las tabelas de trade, execute o seguinte bloco de código SQL:

```sql
CREATE DATABASE sistema_day_trade;
USE sistema_day_trade;
```

---

##  Planeamento e Tarefas

Aqui encontra-se a lista detalhada com o estado de desenvolvimento de todas as funcionalidades exigidas pelo plano do projeto:

* **Controlo de Risco:** Definição automatizada de limites máximos de perda (*stop loss*) e metas de lucro (*take profit*).
* **Histórico Detalhado:** Listagem completa de todos os ativos negociados com as respetivas datas e horários de entrada e saída.

### O que já está feito

- [x] Criar a folha de texto estruturada chamada README.md.
- [x] Escrever o título principal e a descrição do sistema no topo da página.
- [x] Adicionar o logótipo e a tabela de tecnologias com alinhamentos formatados.
- [ ] Implementar a ligação direta à interface de utilizador na internet.

##  Autor

* **Desenvolvedor:** Jean — saiba mais sobre este e outros projetos financeiros visitando o meu [Perfil do GitHub](https://github.com).
