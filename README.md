# 🛼 Snitap - Landing Page Patins Animada

Este projeto é uma landing page interativa e vibrante para a marca de patins Snitap, focada em proporcionar uma experiência visual engajadora através de animações modernas e um design responsivo construído com uma sólida arquitetura **Mobile-First**.

## ✨ Visão Geral

A página foi desenvolvida com forte apelo visual, apresentando os produtos de forma dinâmica e divertida. O grande diferencial desta versão é a aplicação aprimorada de conceitos avançados de CSS. O projeto foi refatorado para garantir uma adaptação perfeita entre dispositivos (celulares, tablets e desktops) utilizando media queries progressivas (`min-width`) e animações dinâmicas que recalculam valores matemáticos com base no tamanho da tela.

## 🛠️ Tecnologias Utilizadas

[![My Skills](https://skillicons.dev/icons?i=html,css)](https://skillicons.dev)

- **HTML5**: Estruturação semântica e acessível da página.
- **CSS3**: Estilização com variáveis (Custom Properties), CSS Grid, Flexbox e arquitetura Mobile-First.
- **Animações CSS**: Uso avançado de `@keyframes` dinâmicos integrados com variáveis CSS e a propriedade moderna `animation-timeline: view()` para efeitos ativados pelo scroll.

## 🚀 Como Usar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/marciosykes/lp-patins-animada.git](https://github.com/marciosykes/lp-patins-animada.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd lp-patins-animada
    ```
3.  **Abra o projeto:**
    Basta abrir o arquivo `index.html` no seu navegador preferido ou utilizar a extensão *Live Server* do VS Code para visualizar com recarregamento automático.

## 💡 Funcionalidades e Destaques (Atualizado)

-   **Arquitetura Mobile-First Aprimorada**: O CSS foi estruturado para carregar primeiro os estilos de dispositivos móveis, utilizando media queries `@media (min-width: ...)` para aprimorar progressivamente o layout para tablets (768px) e desktops (1024px). Isso resultou em um código mais limpo e melhor performance.
-   **Animações Dinâmicas com CSS Variables**: O efeito de rolagem de palavras no título principal (`h1`) agora utiliza a variável `--slide-h`. O CSS calcula automaticamente a distância da animação multiplicando o tamanho da fonte pela altura da linha para cada breakpoint, impedindo que o texto quebre ou fique desalinhado em telas menores.
-   **Animações ao Rolar a Página**: A galeria de imagens utiliza `animation-timeline: view()` e a propriedade `data-delay` para criar um efeito em cascata suave conforme o usuário rola o site para baixo.
-   **Layout Adaptável e Inteligente**: Seções inteiras, como o cabeçalho, a galeria (de 1 para 2 colunas até um grid assimétrico) e o rodapé, alteram sua estrutura (`flex-direction` e `grid-template-areas`) de forma fluida dependendo do dispositivo.

## 📸 Screenshots do Frontend

### Versão Desktop & Mobile

<div align="center">
  <img src="./assets/images/demo snitap.gif" alt="Demonstração das animações da Landing Page de Patins" width="800px">
</div>

## 🔮 Melhorias Futuras

-   Implementar a abertura de um modal de vídeo ao clicar no botão "Play" da seção Hero.
-   Adicionar um botão de "Voltar ao topo" que surge após o usuário rolar uma certa porcentagem da tela.
-   Criar um menu "Hamburger" interativo para a navegação mobile.

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tem ideias para melhorar este projeto, sinta-se à vontade para:

1.  Fazer um fork do repositório.
2.  Criar uma nova branch (`git checkout -b feature/sua-feature`).
3.  Fazer suas alterações e commit (`git commit -m 'Adiciona nova feature'`).
4.  Enviar para a branch (`git push origin feature/sua-feature`).
5.  Abrir um Pull Request.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.