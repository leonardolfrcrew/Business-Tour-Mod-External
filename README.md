# Business Tour Mod — Correções e Adaptações

Projeto derivado do **Business Tour Mod External**, originalmente desenvolvido por **Nebulea-dev**.

Este repositório reúne versões corrigidas e adaptadas do mod original para o jogo Business Tour. O objetivo é preservar a ideia e os recursos do projeto original, corrigindo problemas de compatibilidade e ajustando o funcionamento para builds mais recentes do jogo.

**Créditos:** O projeto original e sua implementação inicial pertencem a **Nebulea-dev**. Este repositório não reivindica a autoria do mod original. As alterações, correções e adaptações presentes nesta distribuição devem ser atribuídas aos responsáveis por esta versão.

---

## Sobre as versões

Atualmente, este repositório contém dois executáveis independentes, cada um com foco em um modo de uso específico:

| Arquivo | Foco e Descrição |
| :--- | :--- |
| `Business Tour 2.0.exe` | **Focado em Partidas Online:** Versão adaptada para Business Tour 2.0, com leitura da partida em tempo real, seleção de jogadores e controles de valores e efeitos otimizados para o ambiente multiplayer. |
| `Business Tour Mod.exe` | **Focado em Partidas com Amigos / Privadas:** Versão modernizada do mod, com controles de bônus/extras e funções avançadas para gerenciamento da partida. |

> **Aviso:** As duas aplicações são independentes. **Não execute os dois mods ao mesmo tempo.** A própria aplicação apresenta avisos para fechar outra instância do mod antes de ativar determinados efeitos ou alterar valores.

---

## Recursos

Os recursos identificados nos executáveis incluem:

* Conexão com o processo do Business Tour.
* Leitura e atualização dos dados da partida em tempo real.
* Identificação e seleção de jogadores.
* Controles de saldo, incluindo adicionar ou remover valores.
* Controles relacionados ao contador de prisão.
* Opções relacionadas a bônus e extras (dados, duplos, cartas e relançamentos).
* Verificações de turno, tela e estado da partida para habilitar determinadas funções.
* Desativação de efeitos e solicitação de reconexão quando a partida muda.

> **Importante:** A disponibilidade de cada recurso depende da versão do jogo, do modo de partida, do turno e da tela atual. Nem todos os caminhos foram validados em uma partida real. Consulte as mensagens exibidas pelo próprio programa e confirme o resultado dentro do jogo.

---

## O que este projeto modifica

Esta distribuição tem como base o trabalho de Nebulea-dev e busca corrigir/adaptar o funcionamento do mod para uma versão mais recente do Business Tour.

As alterações específicas desta versão devem ser documentadas nos commits e nas notas de cada release. Não atribuímos ao projeto original correções que foram feitas nesta continuação.

---

## Build identificada

Durante a análise dos executáveis, foi encontrada uma referência à **build 25994541** do jogo. Isso não garante compatibilidade com todas as instalações ou atualizações.

Atualizações do Business Tour podem alterar estruturas e endereços de memória, fazendo com que algumas funções deixem de funcionar até que o mod seja atualizado.

---

## Requisitos

* **Sistema Operacional:** Windows 64 bits.
* **Jogo:** Business Tour instalado e aberto.
* **Estado:** Jogo carregado em uma partida ou sala.
* **Compatibilidade:** Versão do jogo compatível com a build para a qual o executável foi adaptado.

Os executáveis analisados são aplicativos Windows x64 desenvolvidos em C#/.NET. A versão exata do runtime necessária pode variar conforme o ambiente.

---

## Instalação e uso

1. Baixe o executável desejado na seção **Releases** (escolha entre a versão 2.0 para online ou a versão Mod para jogar com amigos).
2. Abra o Business Tour.
3. Entre em uma partida/sala e aguarde o carregamento completo.
4. Execute **somente um** dos executáveis.
5. Use a opção de **conectar/atualizar** para localizar a partida.
6. Selecione o jogador, quando necessário.
7. Ative apenas os recursos compatíveis com o turno e com o modo de jogo atual.
8. Confira o resultado no próprio jogo.

Se a partida mudar, o jogo fechar ou o programa perder a conexão, reconecte antes de tentar utilizar os controles novamente.

---

## Solução de problemas

| Problema | Possível solução |
| :--- | :--- |
| **O jogo não é encontrado** | Abra o Business Tour antes de iniciar o executável. |
| **Jogadores não aparecem** | Atualize/reconecte após entrar na partida. |
| **A partida mudou** | Reconecte; alguns efeitos são desativados automaticamente. |
| **Outro mod está aberto** | Feche a outra versão antes de continuar. |
| **Bônus indisponíveis** | Confira o turno, a tela atual e as regras da sala. |
| **O mod parou após atualização** | A build pode ter mudado; aguarde uma versão compatível. |
| **Um valor não foi atualizado** | Não repita a operação imediatamente; reconecte e confira o estado da partida. |

---

## Avisos e Limitações

* **Partidas Multiplayer / Online:** O mod **funciona em partidas multiplayer**, porém o jogo possui um sistema de leitura e validação de dados em tempo real com o servidor. Modificar valores diretamente (como dinheiro) pode causar dessincronização entre a memória local injetada e o estado no servidor. Isso frequentemente resulta na **desconexão da partida** (às vezes o jogo reconecta e restaura o estado anterior, às vezes não).
* **Risco de Sanções:** A modificação de dados de memória em ambientes online pode violar os Termos de Serviço do jogo e acarretar sanções ou banimento da conta.
* **Uso Recomendado:** Utilize preferencialmente a versão `Business Tour Mod.exe` para partidas privadas com amigos e testes, para evitar desconexões por validação de servidor.
* **Sem Garantias:** Este projeto é fornecido "como está", sem garantias de funcionamento, compatibilidade continuada ou suporte pós-atualização do jogo.
* **Segurança:** Baixe executáveis somente de fontes confiáveis.

---

## Créditos e projeto original

* **Autor do projeto original:** Nebulea-dev
* **Repositório original:** `Nebulea-dev/Business-Tour-Mod-External`

Este repositório é uma continuação não oficial com correções e adaptações. Consulte o repositório original para conhecer a implementação inicial, o histórico e os créditos do projeto-base.

---

## Integridade dos executáveis analisados

Hashes SHA-256 dos arquivos analisados nesta distribuição:

| Arquivo | SHA-256 |
| :--- | :--- |
| `Business Tour 2.0.exe` | `628b8d3aa30f3bc1853914610fabb109b3c9ab4dd4bde58f27f9ab250dc7f64f` |
| `Business Tour Mod.exe` | `2d25d1eb25f5466fdcd335dfa3cbd527daf61311005ce1c4a074a72da17f4056` |

---

**Status:** Versão adaptada em desenvolvimento. A compatibilidade e todos os recursos precisam ser revalidados após atualizações do Business Tour.
