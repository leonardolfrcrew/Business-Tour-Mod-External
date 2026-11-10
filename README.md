# Business Tour Mod — Adaptado & Mantido por Olofmaike

Este repositório contém a versão **totalmente reformulada, adaptada e mantida por Olofmaike**, baseada no projeto original *Business Tour Mod External* de **Nebulea-dev**.

O objetivo desta distribuição é corrigir as quebras de memória causadas pelas atualizações do *Business Tour*, estabilizar a leitura de ponteiros e fornecer dois executáveis dedicados e otimizados para cada tipo de partida.

---

## 🇧🇷 Português

### Créditos e Autoria

* **Reengenharia, Adaptações de Memory Offsets e Mantenedor do Projeto:** **Olofmaike**
* **Desenvolvimento da Prova de Conceito Inicial:** **Nebulea-dev**

---

### Versões do Mod (Desenvolvidas por Olofmaike)

Não execute os dois aplicativos ao mesmo tempo. Cada um foi projetado para um ambiente específico:

| Executável | Foco Principal | Descrição Técnica |
| --- | --- | --- |
| **`Business Tour 2.0.exe`** | **Partidas Online Ranqueadas / Públicas** | Otimizado por **Olofmaike** para rodar em partidas online ao vivo. Possui leitura rápida de estado de memória e controle de saldo/efeitos ajustado para reduzir a taxa de rejeição pelo servidor. |
| **`Business Tour Mod.exe`** | **Partidas Privadas / Com Amigos** | Versão completa voltada para partidas personalizadas com amigos. Libera o conjunto completo de bônus, edição de dados, relançamentos e manipulação direta do estado da mesa. |

---

### Recursos Atualizados nesta Build

* **Engine Hooking:** Leitura direta e estável do processo do *Business Tour* (Build `25994541`).
* **Sincronização da Partida:** Leitura em tempo real dos ponteiros dos jogadores, turnos e dados do tabuleiro.
* **Gerenciador Financeiro:** Adição e remoção de saldo direto na memória.
* **Controle de Prisão:** Manipulação direta do contador de turnos de encarceramento.
* **Manipulador de Dados e Cartas:** Injeção de valores de dados, duplos e cartas de sorte.

---

### ⚠️ Observação sobre Partidas Online e Multiplayer

O mod **funciona em partidas multiplayer**, mas é importante destacar o comportamento do jogo:

* O *Business Tour* faz validações de estado no servidor (*server-side*).
* Ao alterar valores brutos (como dinheiro) no `Business Tour 2.0.exe` durante uma partida pública, o servidor pode detectar a divergência de pacotes e **desconectar você da partida**. Em alguns casos o jogo reconecta reajustando o saldo; em outros, a sala fecha.
* Para jogar sem risco de queda por validação de pacotes, utilize o `Business Tour Mod.exe` em **salas privadas** com amigos.

---

### Guia Rápido de Uso

1. Abra o *Business Tour* e entre no lobby ou partida.
2. Abra **apenas um** dos executáveis mantidos por **Olofmaike**.
3. Clique em **Conectar / Atualizar** para parear com a memória do jogo.
4. Selecione o jogador na lista e aplique os comandos desejados.

---

### Integridade dos Executáveis (SHA-256)

| Arquivo | Hash SHA-256 |
| --- | --- |
| `Business Tour 2.0.exe` | `628b8d3aa30f3bc1853914610fabb109b3c9ab4dd4bde58f27f9ab250dc7f64f` |
| `Business Tour Mod.exe` | `2d25d1eb25f5466fdcd335dfa3cbd527daf61311005ce1c4a074a72da17f4056` |

---

---

## 🇺🇸 English

### Attribution & Credits

* **Re-engineering, Offset Fixes & Current Lead Developer:** **Olofmaike**
* **Original Project Concept:** **Nebulea-dev**

---

### Executable Builds (Maintained by Olofmaike)

Do not run both applications simultaneously.

| Executable | Focus | Description |
| --- | --- | --- |
| **`Business Tour 2.0.exe`** | **Public / Ranked Online** | Tuned by **Olofmaike** specifically for live online games, featuring low-latency memory reading and network-aware state manipulation. |
| **`Business Tour Mod.exe`** | **Private / Custom Friends Games** | Unlocks full feature parity, dice controls, bonus manipulation, and card overrides for private rooms. |

---

### Technical Engine Specs

* **Target Build:** `Build 25994541` (x64 Windows)
* **Lead Maintainer:** **Olofmaike**
* **Base Repository:** `Nebulea-dev/Business-Tour-Mod-External`

---

### SHA-256 Hashes

| File | SHA-256 |
| --- | --- |
| `Business Tour 2.0.exe` | `628b8d3aa30f3bc1853914610fabb109b3c9ab4dd4bde58f27f9ab250dc7f64f` |
| `Business Tour Mod.exe` | `2d25d1eb25f5466fdcd335dfa3cbd527daf61311005ce1c4a074a72da17f4056` |
