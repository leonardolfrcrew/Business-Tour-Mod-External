Business Tour Mod — Correções e Adaptações
Projeto derivado do Business Tour Mod External, originalmente desenvolvido por Nebulea-dev.

Este repositório reúne versões corrigidas e adaptadas do mod original para o jogo Business Tour. O objetivo é preservar a ideia e os recursos do projeto original, corrigindo problemas de compatibilidade e ajustando o funcionamento para builds mais recentes do jogo.
Créditos: o projeto original e sua implementação inicial pertencem a Nebulea-dev. Este repositório não reivindica a autoria do mod original. As alterações, correções e adaptações presentes nesta distribuição devem ser atribuídas aos responsáveis por esta versão.

Sobre as versões
Atualmente, este repositório contém dois executáveis:
Arquivo	Descrição
Business Tour 2.0.exe	Versão adaptada para Business Tour 2.0, com leitura da partida, seleção de jogadores e controles de valores/efeitos
Business Tour Mod.exe	Versão modernizada do mod, com controles de bônus/extras e funções relacionadas à partida


As duas aplicações são independentes. Não execute os dois mods ao mesmo tempo. A própria aplicação apresenta avisos para fechar outra instância do mod antes de ativar determinados efeitos ou alterar valores.
Recursos
Os recursos identificados nos executáveis incluem:
- Conexão com o processo do Business Tour.
- Leitura e atualização dos dados da partida.
- Identificação e seleção de jogadores.
- Controles de saldo, incluindo adicionar ou remover valores.
- Controles relacionados ao contador de prisão.
- Opções relacionadas a bônus e extras, como dados, duplos, cartas e relançamentos.
- Verificações de turno, tela e estado da partida para habilitar determinadas funções.
- Desativação de efeitos e solicitação de reconexão quando a partida muda.
Importante: a disponibilidade de cada recurso depende da versão do jogo, do modo de partida, do turno e da tela atual. Nem todos os caminhos foram validados em uma partida real. Consulte as mensagens exibidas pelo próprio programa e confirme o resultado dentro do jogo.
O que este projeto modifica
Esta distribuição tem como base o trabalho de Nebulea-dev e busca corrigir/adaptar o funcionamento do mod para uma versão mais recente do Business Tour.

As alterações específicas desta versão devem ser documentadas nos commits e nas notas de cada release. Não atribuímos ao projeto original correções que foram feitas nesta continuação.
Build identificada
Durante a análise dos executáveis, foi encontrada uma referência à build 25994541 do jogo. Isso não garante compatibilidade com todas as instalações ou atualizações.

Atualizações do Business Tour podem alterar estruturas e endereços de memória, fazendo com que algumas funções deixem de funcionar até que o mod seja atualizado.
Requisitos
- Windows 64 bits.
- Business Tour instalado.
- Jogo aberto e carregado em uma partida/sala.
- Versão do jogo compatível com a build para a qual o executável foi adaptado.
Os executáveis analisados são aplicativos Windows x64 desenvolvidos em C#/.NET. A versão exata do runtime necessária pode variar conforme o ambiente.
Instalação e uso
1. Baixe o executável desejado na seção Releases.
2. Abra o Business Tour.
3. Entre em uma partida/sala e aguarde o carregamento.
4. Execute somente um dos executáveis.
5. Use a opção de conectar/atualizar para localizar a partida.
6. Selecione o jogador, quando necessário.
7. Ative apenas os recursos compatíveis com o turno e com o modo de jogo atual.
8. Confira o resultado no próprio jogo.
Se a partida mudar, o jogo fechar ou o programa perder a conexão, reconecte antes de tentar utilizar os controles novamente.
Solução de problemas
Problema	Possível solução
O jogo não é encontrado	Abra o Business Tour antes de iniciar o executável
Jogadores não aparecem	Atualize/reconecte após entrar na partida
A partida mudou	Reconecte; alguns efeitos são desativados automaticamente
Outro mod está aberto	Feche a outra versão antes de continuar
Bônus indisponíveis	Confira o turno, a tela atual e as regras da sala
O mod parou após uma atualização do jogo	A build pode ter mudado; aguarde uma versão compatível
Um valor não foi atualizado no jogo	Não repita a operação imediatamente; reconecte e confira o estado da partida


Avisos
- Use preferencialmente em partidas privadas ou ambientes de teste.
- Modificar a memória do jogo pode causar comportamentos inesperados.
- Não há garantia de funcionamento em partidas online ou multiplayer.
- O uso de ferramentas de modificação pode violar os termos do jogo e resultar em sanções.
- Faça backup de dados importantes, quando aplicável.
- Baixe executáveis somente de fontes em que você confia.
Este projeto é fornecido "como está", sem garantias de funcionamento, compatibilidade ou suporte.
Créditos e projeto original
- Autor do projeto original: Nebulea-dev
- Repositório original: Nebulea-dev/Business-Tour-Mod-External
Este repositório é uma continuação não oficial com correções e adaptações. Consulte o repositório original para conhecer a implementação inicial, o histórico e os créditos do projeto-base.
Integridade dos executáveis analisados
Hashes SHA-256 dos arquivos analisados nesta distribuição:
Arquivo	SHA-256
Business Tour 2.0.exe	628b8d3aa30f3bc1853914610fabb109b3c9ab4dd4bde58f27f9ab250dc7f64f
Business Tour Mod.exe	2d25d1eb25f5466fdcd335dfa3cbd527daf61311005ce1c4a074a72da17f4056


Status: versão adaptada em desenvolvimento. A compatibilidade e todos os recursos precisam ser revalidados após atualizações do Business Tour.
