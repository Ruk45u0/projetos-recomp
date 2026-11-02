# projetos-recomp
Lista organizada com os melhores projetos de recompilação de jogos, além de forks de emulação para jogos específicos (demon's souls remake, por exemplo)
> ⚠️ Nenhum projeto aqui distribui jogos ou assets protegidos. A maioria exige que você tenha sua própria cópia legal do jogo.

## Índice

- [Recompilações](#recompilações)
  - [Nintendo Switch](#nintendo-swicth)
- [Ports Nativos](#ports-nativos)
  - [PlayStation 4](#playstation-4)
  - [Xbox One](#xbox-one)
- [Emuladores](#emuladores)
  

## Legenda de status

- 🟢 Ativo e jogável
- 🟡 Experimental ou em estágio inicial
- 🔴 Abandonado
- ✅ Completo

## Recompilações

Recompilação estática: o código do console é traduzido para código nativo do PC.

### Nintendo Switch
- **Bayonetta 2** - [B2recomp](https://github.com/K0NL/B2recomp) - Recompilação do jogo (v1.2) para Windows, com Linux em testes. Capítulo 1 jogado com controle, 60 FPS, modo 120 FPS (beta), HDR, mods e launcher próprio. `Windows` `Linux (testes)` `GPL-3.0` 🟢
- **Bayonetta 3** - [Witch-Time](https://github.com/Zexyen/Witch-Time) - Recompilação baseada no B2recomp. Roda e joga a 60 FPS (testado em Tóquio e Shibuya), com resolução interna ajustável até 4K e painel de configurações no jogo. `Windows` `Linux` `GPL-3.0` 🟢
- **The Legend of Zelda: Breath of the Wild** - [SavageWindRecomp](https://github.com/Revivedx/SavageWindRecomp) - Recompilação da v1.8.2, baseada no LAS Recomp. Ainda não jogável: chega ao menu e à abertura no Santuário da Ressurreição (Alpha 1 para testadores). `Windows` `Linux` `MIT` 🟡
- **The Legend of Zelda: Tears of the Kingdom** - [totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) - Recompilação para Windows com renderizador Vulkan. Jogável, 60 FPS por padrão (até 144 em modo experimental), FSR 1, giroscópio e menu no jogo. Suporta as atualizações 1.2.1 e 1.4.3. `Windows` `MIT` 🟢

## Ports Nativos

O código original roda direto na CPU, com uma camada de sistema reimplementada.

### Playstation 4

- **Bloodborne** - [bloodborne_pc (fork Windows)](https://github.com/Supermedo/bloodborne_pc) - Fork de [deadinside28/bloodborne_pc](https://github.com/deadinside28/bloodborne_pc) com build para Windows e launcher. Roda a v1.09 com FPS destravado e upscaling FSR 3.1/4/4.1.1. Experimental: jogável, mas sem zerada verificada. `Windows` `Linux` `GPL-2.0` 🟡
- **God of War III Remastered** - [SpartanPort](https://github.com/FelipePrado0/SpartanPort) - Fork do bloodborne_pc (antes chamado gow3_pc). Launcher, menu no jogo, ícones de botões, ultrawide (beta) e até 240 FPS. `Windows` `Linux (AppImage experimental)` `GPL-2.0` 🟢
- **Shadow of the Colossus** - [ShadowOfTheColossus-PC](https://github.com/AjncSystem/ShadowOfTheColossus-PC) - Port para Windows (CUSA08809, EU 1.01 recomendada). O jogo já pode ser zerado do início ao fim, com texturas de alta qualidade, modo PS4 Pro, 60 FPS e widescreen. `Windows` `GPL-2.0` 🟢
- **The Last Guardian** - [tlg_pc](https://github.com/HayatoG/tlg_pc) - Port da versão 1.03, a 30 FPS estáveis (60 FPS e livre experimentais), com SMAA/CAS, mouse e teclado e giroscópio. Testado no Linux; o build para Windows ainda não foi testado em jogo. README em português. `Linux` `Windows (não testado)` `GPL-2.0` 🟢

### Xbox One

- [Azimuth](https://almost-there-games.itch.io/azimuth) - Wrapper de compatibilidade que roda jogos de Xbox One no PC. Começou com *Forza Horizon 2* e hoje também roda *Forza Motorsport 5*, *Forza Motorsport 6* e *Forza Horizon 3*. Inclui launcher com presets gráficos, 30/60 FPS e opções de resolução e antisserrilhado. Funciona no Steam Deck via Proton. Distribuído pelo itch.io. Exige cópia legítima do jogo. `Windows 11` `Linux` 🟢

## Emuladores

### Playstation 5

- [KytyPS5 (fork do chenxiao07)](https://github.com/chenxiao07/KytyPS5) - Emulador de PS5 em C++. Fork do [KytyPS5](https://github.com/KytyPS5/KytyPS5), que deriva do [Kyty](https://github.com/InoriRus/Kyty). Nos meus testes, foi o fork com melhor desempenho em *Demon's Souls* (remake). Atualizado quase diariamente. Requer cópia legal do jogo. `PS5` `Windows` `Linux` `macOS (experimental)` `GPL-2.0` 🟢

## Como contribuir

Sugestões são bem-vindas! Abra uma *issue* ou um *pull request* seguindo o formato das entradas acima.
