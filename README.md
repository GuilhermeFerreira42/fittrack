# FitTracker Pro

## 1. Descrição

O **FitTracker Pro** é uma aplicação web front-end desenvolvida para ser uma planilha de treino digital, interativa e pessoal. O sistema foi projetado para substituir planilhas estáticas (físicas ou em softwares como Excel), oferecendo uma experiência de usuário moderna, responsiva e com salvamento automático de dados.

O usuário pode navegar por 12 semanas de treino distintas, registrar suas cargas e repetições para cada exercício e ter a certeza de que seu progresso será salvo diretamente em seu navegador, garantindo total privacidade e funcionamento offline.

## 2. Status do Projeto

**Concluído (Fase 1)**

* Toda a estrutura de front-end está implementada.
* As **12 semanas** de treino estão completas e funcionais.
* A funcionalidade de persistência de dados no `localStorage` está 100% operacional.

**Próximos Passos (Fase 2)**

* Evoluir a tela de **Dashboard** para incluir:
    * Um botão para **download** de todos os dados de treino do usuário em formato JSON.
    * **Métricas** e gráficos visuais para acompanhar a evolução de cargas e repetições ao longo do tempo.

## 3. Como Utilizar

Por ser uma aplicação totalmente client-side, não há necessidade de instalação ou servidor.

1.  Salve o arquivo `index.html` em seu computador.
2.  Abra o arquivo `index.html` em qualquer navegador de internet moderno (Google Chrome, Firefox, Edge, etc.).
3.  Pronto! Comece a usar a aplicação.

## 4. Funcionalidades

* **12 Semanas de Treino Detalhadas:** Planos de treino completos, divididos por dia da semana, de segunda a sábado.
* **Registro de Progresso:** Campos de entrada para registrar o peso (kg) e as repetições (reps) de cada série realizada.
* **Salvamento Automático:** Os dados inseridos são salvos automaticamente no `localStorage` do navegador assim que o campo é alterado. Não é preciso clicar em um botão "Salvar".
* **Persistência de Dados:** Ao recarregar ou reabrir a página, todos os dados previamente inseridos são carregados novamente, garantindo que o progresso não seja perdido.
* **Navegação Intuitiva:** Um menu lateral (sidebar) recolhível permite navegar facilmente entre as 12 semanas de treino e o Dashboard.
* **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, de desktops a dispositivos móveis.
* **Privacidade Total:** Todos os dados do usuário são armazenados localmente. Nenhuma informação é enviada para um servidor externo.

## 5. Tecnologias Utilizadas

O projeto foi construído utilizando apenas tecnologias front-end:

* **HTML5:** Para a estrutura semântica da aplicação.
* **Tailwind CSS:** Um framework CSS utility-first para a estilização rápida e moderna, incluído via CDN.
* **JavaScript (Vanilla):** Para toda a lógica da aplicação, incluindo manipulação do DOM, gerenciamento de eventos e a interação com a API `localStorage`.