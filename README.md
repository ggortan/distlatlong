# Calculadora de Distâncias com Mapa

Este é um projeto web simples para calcular e visualizar distâncias entre pontos geográficos em um mapa interativo.

![screenshot](https://github.com/user-attachments/assets/e677851f-be87-4bd2-bb9d-7179a2511689)


## Funcionalidades

- **Cálculo de Distâncias:** Insira coordenadas para calcular a distância entre dois pontos.
- **Visualização no Mapa:** Os pontos e as linhas de distância são exibidos no mapa.
- **Tabela de Resultados:** As distâncias calculadas são listadas em uma tabela, com um total.
- **Destaque Interativo:** Clique em uma linha da tabela para destacar os pontos correspondentes no mapa.
- **Exportar/Importar TXT:** Salve ou carregue coordenadas de um arquivo de texto.
- **Limpar Dados:** Opção para remover todos os resultados do mapa e da tabela.

## Como Usar

1. **Abrir o `index.html`:** Basta abrir o arquivo `index.html` em qualquer navegador web.
2. **Inserir Coordenadas:** Na caixa de texto à esquerda, digite as coordenadas no formato `lat1 long1 lat2 long2` por linha.  
   Exemplo:
   ```
    -22.725165 -47.6493269 -22.9056391 -47.059564
    -23.550520 -46.633308 -22.906847 -43.172896
   ```

4. **Calcular:** Clique no botão "Calcular" para ver os pontos no mapa e os resultados na tabela.
5. **Interagir:** Clique nas linhas da tabela para destacar os pontos no mapa.

## Botões de Ação

- **Calcular:** Processa as coordenadas e atualiza o mapa e a tabela.
- **Limpar:** Remove todos os marcadores, linhas e resultados da tabela.
- **Exportar TXT:** Salva as coordenadas atuais da caixa de texto em um arquivo `.txt`.
- **Importar TXT:** Carrega coordenadas de um arquivo `.txt` para a caixa de texto.

## Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **CSS3:** Estilização básica.
- **JavaScript:** Lógica da aplicação.
- **Bootstrap 5.3:** Componentes de UI e responsividade.
- **Leaflet 1.9:** Biblioteca para mapas interativos.
- **OpenStreetMap:** Provedor de tiles para o mapa.

## Autor

- **Gabriel Gortan**  
[LinkedIn](https://www.linkedin.com/in/gabrielgortan/)
