# Loading Data Perform

# Animação de Carregamento com Logo

Este projeto demonstra uma animação criativa de carregamento para um site utilizando HTML5, CSS3, Bootstrap e JavaScript. A animação apresenta um logo dividido em duas partes, cada uma girando em sentidos opostos, criando um efeito visual dinâmico. Abaixo do logo, há um botão com o texto "Acessar o site", que redireciona os usuários para o site principal.

## Funcionalidades

- **Animação Rotativa do Logo**: O logo é dividido em duas camadas (clara e escura), cada uma girando em sentidos opostos para criar um efeito atraente.
- **Efeito Hover**: Quando o usuário passa o mouse sobre o logo, ele aumenta ligeiramente de tamanho para maior destaque.
- **Botão Call-to-Action**: Um botão abaixo do logo redireciona os usuários para um site especificado.
- **Design Responsivo**: A animação e o layout são responsivos, garantindo compatibilidade com diferentes tamanhos de tela.

## Tecnologias Utilizadas

- **HTML5**: Estrutura de marcação do projeto.
- **CSS3**: Estilização e animações.
- **Bootstrap 5**: Para design e layout responsivo.
- **JavaScript**: Para manipular interações do botão e animações.

## Como Usar

1. Clone este repositório ou faça o download dos arquivos do projeto.
2. Certifique-se de ter o seguinte ativo:
   - `Logo_preta_transp.png`: Um arquivo PNG transparente do seu logo.
3. Substitua o URL de exemplo no atributo `onclick` do botão pelo URL desejado do site:
   ```html
   <button class="access-button" onclick="window.location.href='https://www.seusite.com';">Acessar o site</button>
   ```
4. Abra o arquivo `index.html` no navegador para visualizar a animação.

## Personalização

- **Tamanho do Logo**: Ajuste o tamanho do logo modificando as propriedades `width` e `height` da classe `.logo-container` no CSS.
- **Velocidade da Animação**: Altere a duração da animação de rotação editando o valor `2s` nas definições de `@keyframes`:
  ```css
  @keyframes spinClockwise {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(360deg);
    }
  }
  ```
- **Estilo do Botão**: Modifique a aparência do botão alterando a classe CSS `.access-button`.

## Licença

Este projeto é open-source e está disponível para modificação e distribuição sob a licença MIT. 
### Criado por BArcellos ↟ / Cellão.

