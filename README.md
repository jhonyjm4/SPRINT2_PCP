# ⚡ ChargeGrid Intelligence (CGI) - Comercial
> **EV Challenge 2026** | Prova de Conceito (PoC) desenvolvida no Google Colab.
> **Equipe 4 - 1CCPG**

---

### 👥 Integrantes
* **João Marcelo** - RM: 572569
* **Lucas Barreto** - RM: 573149
* **Pablo Renato** - RM: 569894
* **Pedro Vianna** - RM: 570747

---

### 🎯 O Projeto em 3 Pilares
Evoluímos os conceitos da Sprint 1 para uma aplicação prática que resolve o gargalo de carregamento em redes comerciais compartilhadas:

1. **Gestão Inteligente de Demanda:** O algoritmo lê o *Smart Meter* e o Inversor Linha ET para redistribuir a corrente sem derrubar os disjuntores do comércio.
2. **IA ChargeOps:** Chatbot nativo com técnica *Chain of Thought* para acalmar o cliente e explicar variações de carga com base nos manuais GoodWe.
3. **Tarifação Direta:** Simulação de checkout via QR Code Pix diretamente nos carregadores HCA.

---

### 🏗️ Fluxo Lógico do Sistema

[Smart Meter] ➔ Mede o consumo do prédio em tempo real.
│
▼
[Inversor GoodWe Linha ET] ➔ Calcula a sobra de energia.
│
├─► Sobra Pouca? Orquestração Ativa (Reduz corrente dos carregadores).
│
└─► Cliente em Dúvida? [Chatbot ChargeOps] explica a variação da rede.


---

### 🚀 Como Executar no Google Colab (Passo a Passo)

A nossa Prova de Conceito foi desenhada especificamente para o ambiente interativo do **Google Colab**, gerando relatórios de texto e gráficos dinâmicos de consumo.

1. **Abra o arquivo do projeto** diretamente no Google Colab.
2. Copie o código contido no repositório para uma célula do caderno.
3. Clique em **Executar** (`Play` ou `Ctrl + Enter`).
4. **O que vai acontecer?** * O sistema simulará um pico de consumo no prédio com 3 carros carregando ao mesmo tempo.
   * O gráfico gerado mostrará a **Orquestração Ativa** contendo a energia sem passar do limite da rede.
   * O Chatbot simulará o atendimento ao usuário explicando o motivo da oscilação de velocidade.
🔗 **Link para o nosso Google Colab:** https://colab.research.google.com/drive/130Y8xVqkXrWTsxQVajj1_5wiXpsUAbEF?usp=sharing

---

### 📊 Organização Ágil (Kanban)
Toda a gestão de tarefas, divisão de papéis e evolução prática da Sprint 2 foi coordenada publicamente.
🔗 **Link para o nosso Quadro Kanban:** https://trello.com/invite/b/6a307387829e5784f3bd46a8/ATTI8c2c67868b4185d83a78d23711165580155F450B/sprint-2-pcp

---

### 🎥 Vídeo Pitch (YouTube)
Vídeo mostrando e aplicando todo o processo do projeto e sua evolução.
🔗 **Link para o nosso vídeo pitch no YouTube:**
