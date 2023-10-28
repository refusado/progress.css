
![Progress.css](./assets/banner.png)

A simple and dynamic way to create horizontal and/or circular progress bars in your HTML without javascript.You can customize it however you like, but only one attribute is needed to make the magic happen 😌 🪄 

## 👀 Demo 

  
[**Click here to try it on Codepen!**](https://codepen.io/pen?template=PoxwVQM)

<details>
  <summary>Show video</summary>
  
  https://github.com/refusado/progress.css/assets/89546855/09c44cb6-c1a2-4ebc-8c52-3ffc0721ceb0

</details>

## 🦾 Features
- Easily create horizontal and circular progress bars.
- No javascript is required.
- Insert labels/texts.
- Customize colors and sizes quickly and easily.
- Its not necessary to modify the HTML, only one element to add the attribute.
- Edit the progress bar as any element on the page without worrying about breaking styles.
- Create groups of multiple progress bars.
- Simple and intuitive implementation.

## 🔨 Getting Started
To start using the Progress.css, follow these steps:

1. Include the CSS file in your project:

    #### Using npm
    Install
    ```
    npm install progress.css
    ```
    And include the file in your html
    ```html
    <link rel="stylesheet" href="path/to/progress.css">
    ```
    #### Via CDN
    You can also just include the file in your html via CDN without installing.
    ```html
    <link rel="stylesheet" href="https://unpkg.com/progress.css/progress.min.css">
    ```
    Or:
    ```html
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/refusado/progress.css/progress.min.css">
    ```
    #### CSS import 
    Import a CDN url into your css file
    ```css
    @import url(https://unpkg.com/progress.css/progress.min.css);
    ```

2. Make your element a progress bar:
    #### One by one
    Add the `data-pss` attribute to your HTML tag and it will become a progress bar. To choose the percentage, type the value of the percentage into the CSS variable `--pss-value`. ⚠️ Do not put the "%" symbol, just the number.
    ```html
    <div data-pss style="--pss-value: 94"></div>
    ```
    
    #### Many at once
    If you want to style several at once, use the `data-pss-container` attribute on the container of the elements you want to turn into progress bars.
    ```html
    <div data-pss-container>
      <div style="--pss-value: 25"></div>
      <div style="--pss-value: 50"></div>
      <div style="--pss-value: 75"></div>
      <div style="--pss-value: 100"></div>
    </div>
    ```


3. Customize the progress bar:
    #### Horizontal and cirular bars
    The `data-pss` attribute will create a horizontal progress bar by default, but if you want a radial progress bar instead,t add the value "rad" to this attribute.

    ```html
      <div data-pss="rad" style="--pss-value: 30"></div>
    ```
    #### Variables
    These are the CSS variables that define the progress bar settings, they all have a default value but can be changed by reassigning the variable value. This can be done either in the document styles CSS file or with inline CSS.

    | Variable                   | Description |
    |----------------------------|-------------|
    | `--pss-value`  | Percentage filled. Default: **65** |
    | `--pss-left`   | Color of the left fill. Default: **#08a33e** |
    | `--pss-right`  | Color of the right fill. Default: **#DDF4F9** |
    | `--pss-center` | Center color of radial progress bars. Default: **#14975a** |
    | `--pss-width`  | Radial progress bar width. Default: **.4rem** |

    #### Texts/labels
    To add text to a horizontal progress bar, use the `aria-label="[text]"` attribute. You can also add the text inside the element's tag, the difference is that this text will not be centered inside the filled part of the bar. It's recommended that you use the first method.

    ```html
    <div data-pss style="--pss-value: 48" aria-label="48%"></div>
    ```
    For radial progress bars there is no additional attribute, just place your text inside the element
    ```html
    <div data-pss="rad" style="--pss-value: 80">8/10</div>
    ```

## 👥 Contributing

Contributions are welcome! If you'd like to contribute to project, please follow these steps:

1. [Fork the repository](https://github.com/refusado/progress.css/fork)  and clone it to your local machine.
2. Make your changes, whether it's a bug fix, feature enhancement, or documentation improvement.
3. Test your changes to ensure they work as intended.
4. Commit your changes with messages.
5. Push your changes to your forked repository.
6. Submit a pull request to the main repository.

Thank you for considering contributing to Progress.css! Your help is greatly appreciated.

## 🖌 Contributors

<a href="https://github.com/refusado/progress.css/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=refusado/progress.css" />
</a>

## 🔓 License

This project is licensed under the  MIT License. See the [LICENSE](https://github.com/refusado/progress.css/blob/main/LICENSE) file for more information about the terms of use.



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Progress.css](./assets/banner.png)

Um jeito simples e dinâmico para criar uma barra de progresso horizontal e/ou circular em seu projeto HTML sem utilizar javascript. Você também pode customizá-la quando e como quiser, apenas um atributo é necessário para fazer a mágica acontecer 😌 🪄 

## 👀 Demonstração 

  
[**Clique aqui para tentar no Codepen!**](https://codepen.io/pen?template=PoxwVQM)

<details>
  <summary>Mostrar vídeo</summary>
  
  https://github.com/refusado/progress.css/assets/89546855/09c44cb6-c1a2-4ebc-8c52-3ffc0721ceb0

</details>

## 🦾 Características
- Criar barras de progresso circulares e horizontais facilmente.
- Javascript não é necessário.
- Insira textos/rótulos.
- Customize as cores e tamanhos de maneira fácil e rápida. 
- Não é necessário modificar o HTML, apenas um elemento para adicionar o atributo. 
- Edite o progresso da barra com qualquer elemento na página sem se preocupar com a quebra dos estilos. 
- Crie múltiplos grupos de barras de progresso. 
- Implementação simples e intuitiva.

## 🔨 Mão na massa
Para iniciar utilizando o Progress.css, siga os seguintes passos:

1. Inclua o arquivo CSS no seu projeto: 

    #### Usando npm
    Instale
    ```
    npm install progress.css
    ```
    E inclua o arquivo no seu HTML
    ```html
    <link rel="stylesheet" href="path/to/progress.css">
    ```
    #### Via CDN
    Você também pode apenas incluir o arquivo no seu HTML via CDN, sem nenhuma instalação. 
    ```html
    <link rel="stylesheet" href="https://unpkg.com/progress.css/progress.min.css">
    ```
    Ou:
    ```html
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/refusado/progress.css/progress.min.css">
    ```
    #### Importar CSS  
    Importe uma url CDN para seu arquivo CSS
    ```css
    @import url(https://unpkg.com/progress.css/progress.min.css);
    ```

2. Faça do seu elemento uma barra de progresso:
    #### Uma por uma
    Adicione o atributo `data-pss` à sua tag HTML e ela se tornará uma barra de progresso. Para escolher a porcentagem, digite o valor dela dentro da variável CSS `--pss-value`. ⚠️ Não use o símbolo de porcentagem “%”, utilize apenas o número.
    ```html
    <div data-pss style="--pss-value: 94"></div>
    ```
    
    #### Várias de uma vez
    Se você quiser editar várias de uma vez, use o atributo `data-pss-container` no contêiner dos elementos que você deseja transformar em uma barra de progresso.
    ```html
    <div data-pss-container>
      <div style="--pss-value: 25"></div>
      <div style="--pss-value: 50"></div>
      <div style="--pss-value: 75"></div>
      <div style="--pss-value: 100"></div>
    </div>
    ```


3. Customize a barra de progresso:
    #### Barras horizontais e circulares
    O atributo `data-pss` criará uma barra de progresso horizontal por padrão, mas se você quiser uma barra de progresso radial, adicione o valor “rad” à esse atributo.
    ```html
      <div data-pss="rad" style="--pss-value: 30"></div>
    ```
    #### Variáveis
    Essas são as variáveis CSS que definem as configurações da barra de progresso, todas possuem um valor padrão, mas podem ser alterados reatribuindo um valor para essa variável. Isso pode ser feito no arquivo CSS de estilos no documento ou em um CSS embutido.

    | Variáveis                   | Descrição |
    |----------------------------|-------------|
    | `--pss-value`  | Preenchimento da porcentagem. Padrão: **65** |
    | `--pss-left`   | Cor do preenchimento esquerdo. Padrão: **#08a33e** |
    | `--pss-right`  | Cor do preenchimento direito. Padrão: **#DDF4F9** |
    | `--pss-center` |Cor central das barras de progresso radiais. Padrão: **#14975a** |
    | `--pss-width`  | Tamanho da barra de progresso radial. Padrão: **.4rem** |

    #### Textos/rótulos
    Para adicionar um texto à uma barra de progresso horizontal, use o atributo `aria-label="[text]"`. Você também pode adicionar o texto dentro da tag do elemento, a diferença é que o texto não ficará centralizado na parte preenchida da barra.  Por isso é recomendado que utilize o primeiro método.
    ```html
    <div data-pss style="--pss-value: 48" aria-label="48%"></div>
    ```
    Para barras de progresso radiais não há nenhum atributo adicional, apenas insira o texto dentro do elemento. 
    ```html
    <div data-pss="rad" style="--pss-value: 80">8/10</div>
    ```

## 👥 Contribuindo para o projeto

Contribuições são bem-vindas! Se você deseja contribuir para o projeto, siga os seguintes passos:

1. [Faça uma bifurcação do repositório](https://github.com/refusado/progress.css/fork)  e copie o arquivo em sua máquina local.
2. Faça suas adaptações, sejam elas uma fixação de um bug, implementação de funcionalidades ou melhoria na documentação.
3. Teste suas alterações para ter certeza de que estão em perfeito funcionamento.
4. Faça uma Commit das alterações com mensagens.
5. Envie suas alterações para o repositório bifurcado.
6. Submeta uma Pull Request para o repositório principal.

Obrigado por considerer contribuir com Project.css! Sua ajuda é muito apreciada. 

## 🖌 Contribuidores

<a href="https://github.com/refusado/progress.css/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=refusado/progress.css" />
</a>

## 🔓 Licença

Esse projeto é licenciado sob a liçenca do MIT. Veja o arquivo [LICENSE](https://github.com/refusado/progress.css/blob/main/LICENSE) para mais informações sobre os termos de uso.






