# 🎲 Business Tour 2.0 — Automation Suite

*Uma aplicação desktop moderna de alta performance projetada para monitoramento e interação em tempo real com o jogo Business Tour.*

[Recursos](#-recursos-principais) • [Instalação](#-instalação-e-execução) • [Guia de Uso](#-guia-de-utilização) • [Créditos](#-créditos-e-contribuições)

## 📋 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Recursos Principais](#-recursos-principais)
- [Requisitos do Sistema](#-requisitos-do-sistema)
- [Instalação e Execução](#-instalação-e-execução)
- [Guia de Utilização](#-guia-de-utilização)
- [Solução de Problemas](#-solução-de-problemas)
- [Créditos e Contribuições](#-créditos-e-contribuições)
- [Isenção de Responsabilidade](#-isenção-de-responsabilidade)

---

## 🛠️ Sobre o Projeto

O **Business Tour 2.0** foi totalmente reformulado para atender às versões e builds mais recentes do jogo. Desenvolvido em C# (.NET Framework), o software combina uma interface gráfica intuitiva baseada em MetroUI com um mecanismo robusto de leitura de memória do processo em tempo real.

Diferente de versões legadas, esta release elimina a necessidade de autenticações manuais, realizando a **detecção e sincronização automática do jogador** assim que a partida é iniciada.

---

## ✨ Recursos Principais

- 🔍 **Detecção Automática de Sessão:** Sincronização automática com a conta e o estado ativo no jogo.
- 🎨 **Interface MetroUI (Dark Mode):** Layout moderno, responsivo e limpo para facilitar a navegação durante as partidas.
- 📊 **Monitor de Eventos em Tempo Real:** Console integrado para acompanhamento detalhado dos logs e status da conexão.
- ⚡ **Alta Performance:** Baixo consumo de memória RAM e processamento otimizado para não impactar a taxa de quadros (FPS) do jogo.
- 📦 **Standalone Distribution:** Pronto para uso diretamente no executável sem necessidade de instaladores complexos.

---

## 💻 Requisitos do Sistema

| Componente | Requisito Mínimo | Requisito Recomendado |
| :--- | :--- | :--- |
| **Sistema Operacional** | Windows 10 (64-bit) | Windows 10 / 11 (64-bit) |
| **Ambiente de Execução** | .NET Framework 4.7.2 | .NET Framework 4.8 |
| **Privilégios** | Administrador | Administrador |
| **Arquitetura** | x64 | x64 |

---

## 🚀 Instalação e Execução

Como este projeto é disponibilizado em formato pré-compilado (`.exe`), siga os passos abaixo para executá-lo corretamente:

1. **Download do Release:**
   Baixe o arquivo `.zip` ou `.rar` mais recente da aba [Releases](../../releases) do repositório.

2. **Extração dos Arquivos:**
   Extraia todo o conteúdo do pacote em uma pasta de sua preferência.

   > ⚠️ **Atenção:** Mantenha as DLLs auxiliares (como `MetroFramework.dll`) na mesma pasta do executável `Business Tour 2.0 - Teste.exe`.

3. **Execução:**
   Clique com o botão direito sobre o executável `Business Tour 2.0 - Teste.exe` e selecione **Executar como Administrador**.

---

## 📖 Guia de Utilização

1. Abra o jogo **Business Tour** e entre em uma partida.
2. Inicie o **Business Tour 2.0** com privilégios de administrador.
3. Aguarde o indicador de status confirmar a vinculação ao processo do jogo.
4. Utilize o painel para monitorar os parâmetros e logs em tempo real.

---

## ❓ Solução de Problemas

- **O programa fecha sozinho ao abrir:** Certifique-se de ter o **.NET Framework 4.7.2** ou superior instalado.
- **Falha ao conectar com o jogo:** Verifique se executou o arquivo com privilégios de **Administrador**.
- **Erro de DLL ausente:** Verifique se extraiu **todos** os arquivos do `.zip` para a mesma pasta. O executável necessita das DLLs no mesmo diretório para inicializar a interface gráfica.
- **Não detecta o jogador:** Certifique-se de abrir o jogo **antes** de inicializar a ferramenta.
- **Antivírus bloqueando:** Verifique se o seu antivírus não bloqueou o processo de leitura de memória da aplicação.

---

## 👥 Créditos e Contribuições

Este projeto é um esforço contínuo da comunidade de desenvolvimento:

- 👤 **Nebulea-dev** — Criador e desenvolvedor da primeira versão do projeto (atualmente legada/obsoleta).
- 👤 **Olofmaike** — Responsável pela manutenção, refatoração completa do código, correção de bugs e atualização do software para suporte total às builds recentes do jogo.

---

## ⚠️ Isenção de Responsabilidade (Disclaimer)

*Este software é disponibilizado estritamente para fins educacionais, demonstrativos e de pesquisa tecnológica. O uso de utilitários de terceiros em ambiente online pode violar os Termos de Serviço (ToS) das plataformas do jogo. Os desenvolvedores e mantenedores não se responsabilizam por eventuais restrições, banimentos ou punições aplicadas às contas dos usuários.*
