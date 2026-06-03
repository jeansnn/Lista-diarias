# 👥 Gestão de Turma | Controle de Presença e Acertos

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um Web App *mobile-first* criado para facilitar a vida de líderes de equipe, encarregados e gestores de campo. Ele automatiza o controle diário de presença, gerencia o limite de transporte (van) e calcula os acertos financeiros pendentes de cada trabalhador de forma rápida e intuitiva.

Ideal para gerenciar equipes em safras, colheitas, construção civil ou qualquer formato de trabalho baseado em diárias.

---

## ✨ Funcionalidades Principais

### 📅 Controle Diário Inteligente
* **Lista de Presença Rápida:** Marque quem foi trabalhar com um simples toque (botões *switch*).
* **Controle de Lotação (Van):** Contador em tempo real que avisa quando o limite de passageiros do transporte (12 vagas) é atingido.
* **Algoritmo de Prioridade:** A lista de presença organiza automaticamente os trabalhadores no topo com base na frequência dos últimos 7 dias (destaque visual verde para quem tem prioridade).
* **Autocompletar Tarefas:** Sugestões inteligentes de atividades baseadas no seu histórico de digitação (ex: Colheita, Cobrir cana, etc).
* **Exportação para WhatsApp:** Gere e copie a lista de presentes do dia já formatada em texto com um clique.

### 👷 Gestão da Equipe e Acertos
* **Perfil Individual:** Toque no nome de um trabalhador para ver o painel exclusivo dele.
* **Acerto Rápido:** Digite o valor da diária atual e o app calcula automaticamente o valor total a ser pago apenas sobre os dias "Pendentes".
* **Histórico de Pagamentos:** Marque serviços específicos como "Pagos" (Zerar) e mantenha um histórico claro do que ainda está "A Receber".
* **Anotações:** Bloco de notas individual para registrar vales, adiantamentos ou observações de produção.

### 📊 Painel e Relatórios
* **Histórico Completo:** Visualize todas as listas passadas, filtre por mês ou por tipo de serviço.
* **Fechamento Mensal:** Gere uma tabela resumida mostrando o total de dias trabalhados por cada membro da equipe em um mês específico.
* **Acumulado por Serviço:** Saiba exatamente quantos dias totais foram gastos em cada atividade.

---

##  Como Executar o Projeto

Este é um projeto **Vanilla Web** (HTML, CSS e JavaScript puros). Não requer banco de dados externo, pois utiliza o `LocalStorage` do próprio navegador do usuário para salvar as informações de forma offline e segura.

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/nome-do-repositorio.git](https://github.com/SEU_USUARIO/nome-do-repositorio.git)
