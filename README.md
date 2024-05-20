

# Homework Week 1

## Descrição
Este projeto é uma página HTML simples que exibe a previsão do tempo para Tóquio. A página contém um cabeçalho, uma lista de previsões para os próximos dias, um botão para alterar a cidade e um rodapé com créditos.

## Pré-requisitos
Para visualizar esta página, você só precisa de um navegador web moderno.

## Instalação
Não há instalação necessária. Basta abrir o arquivo `index.html` em qualquer navegador.

## Uso
1. Clone o repositório para sua máquina local:
    ```sh
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd nome-do-repositorio
    ```
3. Abra o arquivo `index.html` em seu navegador.

## Estrutura do Código
### HTML
- A estrutura principal do arquivo HTML contém um cabeçalho (`<h1>` e `<h2>`) com a temperatura atual e a previsão do dia.
- Uma lista não ordenada (`<ul>`) com a classe `weekdays` exibe as previsões para os próximos dias.
- Um botão (`<button>`) que pode ser utilizado para alterar a cidade.
- Um rodapé (`<footer>`) com créditos.

### CSS
- O estilo é definido diretamente no `<style>` dentro da tag `<head>`.
- Estilização geral para margem, padding e box-sizing.
- Estilização específica para tags como `body`, `h1`, `h2`, `h3`, `li`, `button`, e `p`.
- Efeitos de transição para os itens da lista e para o botão.

### Estrutura do Arquivo
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>homework-week1</title>
    <style>
        /* Estilos CSS aqui */
    </style>
</head>
<body>
    <h1>🌤️ <div>Currently, 21° in Tokyo</div></h1>
    <h2>13°/ <strong> 23° </strong></h2>
    <ul class="weekdays">
        <li>
            <h3><span>🌧️</span> Tomorrow</h3>
            <p>10°/ <strong> 22°</strong></p>
        </li>
        <li>
            <h3><span>🌥️</span> Saturday</h3>
            <p>15°/<strong> 17°</strong></p>
        </li>
        <li>
            <h3><span>🌥️</span> Sunday</h3>
            <p>25°/<strong> 28°</strong></p>
        </li>
    </ul>
    <button type="button" title="Change City">Change City</button>
    <footer>
        <p>Coded by Matt Delac</p>
    </footer>
</body>
</html>
```

## Contribuição
Contribuições são bem-vindas! Por favor, envie um pull request ou abra uma issue para discutir o que você gostaria de mudar.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Esse README fornece uma visão geral clara do projeto, instruções sobre como usá-lo e informações adicionais úteis.
