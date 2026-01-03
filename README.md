# Página Estilizada

Projeto simples para reproduzir a estrutura e o estilo visual de uma página conforme imagem de referência, utilizando propriedades de CSS como Box Model (margin, padding, border) e display (incluindo Flexbox).

## Objetivo
- Criar uma página com:
  - Cabeçalho com o texto “Digital College”
  - Banner roxo logo abaixo do cabeçalho
  - Bloco de conteúdo central com título e parágrafo
  - Seção “Equipe” com três blocos (Team 1, Team 2, Team 3)
  - Rodapé com “todos os direitos reservados”

## Estrutura de Pastas
```
Atividade de CSS/
├── index.html
└── style.css
```

## Como Visualizar
- Abra o arquivo [index.html](file:///e:/CursoGtech/Atividades/Atividade%20de%20CSS/index.html) em qualquer navegador moderno.
- Os estilos estão definidos em [style.css](file:///e:/CursoGtech/Atividades/Atividade%20de%20CSS/style.css).

## Principais Seções (HTML)
- Header: título “Digital College”
- Banner: faixa roxa ampla
- Conteúdo: título “Digital College”, linha decorativa e texto Lorem Ipsum
- Equipe: três cartões com círculo (avatar), nome do time e papel
- Footer: texto de direitos reservados

## Estilos Utilizados (CSS)
- Reset básico: `margin: 0; padding: 0; box-sizing: border-box;`
- Box Model:
  - `padding` e `margin` para espaçamento interno/externo em seções e títulos
  - `border-radius: 50%` para formar os avatares circulares
- Display:
  - `flex` na seção de equipe para alinhamento horizontal e centralização
  - Layout centralizado do “papel” visual usando largura máxima e centralização
- Paleta:
  - Roxo escuro para cabeçalho/rodapé
  - Roxo médio/claro para banner e avatares

## Ajustes Rápidos
- Alterar cores no `:root` do CSS (variáveis `--dark-purple` e `--light-purple`)
- Modificar alturas/larguras do banner e dos círculos em `.hero-banner` e `.circle-avatar`
- Ajustar espaçamentos em `.content-section`, `.team-section` e `.team-grid`

## Observação
Este projeto é puramente estático e não requer dependências ou build. Basta abrir o `index.html`.

👤 Autor
Jardheson Oliveira

Projeto desenvolvido para fins educacionais.
