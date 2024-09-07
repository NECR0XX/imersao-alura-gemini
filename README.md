# Projeto: Busca de Conteúdo em Química - Imersão Dev Alura com Google Gemini

## Descrição
Este projeto web oferece uma interface simples e intuitiva para pesquisar diversos tópicos relacionados à química. Ao digitar uma palavra-chave no campo de pesquisa, o usuário é apresentado a uma lista de resultados relevantes, com título, descrição e link para mais informações.

## Funcionalidades

- **Busca por palavras-chave**: Permite pesquisar por termos específicos relacionados à química.
- **Resultados dinâmicos**: A lista de resultados é atualizada em tempo real conforme o usuário digita.
- **Links externos**: Cada resultado possui um link que direciona o usuário para uma fonte externa com mais detalhes sobre o tópico.

## Tecnologias Utilizadas

- **HTML**: Estruturação da página web.
- **CSS**: Estilização da página, definindo a aparência visual dos elementos.
- **JavaScript**: Lógica da aplicação, responsável por realizar a pesquisa e atualizar a interface.

## Como funciona

1. **Interface do usuário**: O usuário interage com a página através do campo de pesquisa e do botão "Pesquisar".
2. **Processamento da pesquisa**: Ao clicar no botão, o JavaScript coleta o termo de pesquisa e inicia a busca nos dados armazenados em `dados.js`.
3. **Busca nos dados**: O JavaScript percorre os dados, comparando o termo de pesquisa com o título, descrição e tags de cada item.
4. **Exibição dos resultados**: Os resultados encontrados são formatados como HTML e inseridos na seção destinada aos resultados.

## Estrutura de arquivos

- `index.html`: Arquivo principal da página web.
- `style.css`: Arquivo de estilos CSS, responsável pela aparência visual da página.
- `app.js`: Arquivo JavaScript com a lógica da aplicação.
- `dados.js`: Arquivo JavaScript contendo os dados a serem pesquisados (títulos, descrições, tags e links).
