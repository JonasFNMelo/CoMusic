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

## Como rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/JonasFNMelo/CoMusic.git
   ```
2. Abra o projeto no **Xcode** (recomendado Xcode 15 ou superior).
3. Selecione um simulador de iPhone e execute (`⌘R`).

## Autores

- **Jonas Melo**
- **Miqueias Saldanha**

## Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais informações.
