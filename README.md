# CoMusic

Um redesign conceitual do Instagram reimaginado como um aplicativo de música, desenvolvido como estudo prático da **Apple Human Interface Guidelines (HIG)**.

## Sobre o projeto

O CoMusic nasceu de uma proposta de estudo: aprender a fundo as diretrizes de design da Apple aplicando-as em um caso real. Partimos da interface do Instagram e a reconstruímos do zero em SwiftUI, transformando-a em um app voltado para descoberta, compartilhamento e curadoria musical, e alinhando cada decisão visual e de interação às convenções da HIG (hierarquia, navegação, tipografia, espaçamentos, gestos e padrões nativos do iOS).

A ideia central era responder duas perguntas:

- Como seria o Instagram se ele tivesse sido projetado **pela Apple**, seguindo rigorosamente a HIG?
- Como adaptar essa mesma estrutura para um propósito diferente: **música** no lugar de fotos e vídeos genéricos?

## Tecnologias

- **Swift**
- **SwiftUI**
- **Xcode**

## Estrutura do projeto

O app é organizado em torno das principais áreas de navegação, espelhando (e repensando) as seções clássicas do Instagram:

- `Home` — feed principal adaptado para conteúdo musical
- `Search` — descoberta e busca
- `Reels` — vídeos curtos no contexto musical
- `Picker` — seleção de conteúdo
- `Profile`, `Profile2`, `Profile3` — variações de perfil exploradas durante o redesign
- `Assets.xcassets` — recursos visuais do app

> 📸 _Screenshots em breve._

## O que este projeto demonstra

- Aplicação prática da **Human Interface Guidelines**: hierarquia, navegação, tipografia e espaçamentos nativos do iOS
- Reconstrução de uma interface complexa (feed, busca, reels e perfil) inteiramente em **SwiftUI**
- Exploração de alternativas de design: as pastas `Profile`, `Profile2` e `Profile3` guardam variações da tela de perfil testadas durante o redesign

## Como rodar

Este repositório contém o código-fonte e os assets do app, mas não inclui o arquivo `.xcodeproj`. Para executar:

1. Clone o repositório:
   ```bash
   git clone https://github.com/JonasFNMelo/CoMusic.git
   ```
2. No Xcode, crie um novo projeto **iOS › App** com interface **SwiftUI** chamado `CoMusic`.
3. Apague os arquivos `ContentView.swift`, `CoMusicApp.swift` e `Assets.xcassets` gerados pelo template.
4. Arraste todo o conteúdo do repositório para o projeto (marque *Copy items if needed* e *Create groups*).
5. Selecione um simulador de iPhone e execute (`⌘R`).

## Autores

- **Jonas Melo**
- **Miqueias Saldanha**

## Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais informações.
