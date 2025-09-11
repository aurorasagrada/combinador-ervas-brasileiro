# Combinador Mágicko de Ervas

Este é um projeto de um combinador de ervas mágickas, focado em práticas esotéricas e espirituais. A ferramenta permite que o usuário selecione múltiplas ervas e analise a compatibilidade energética entre elas, baseando-se em suas regências planetárias e temperaturas (quente, morna, fria).

## Funcionalidades

- **Seleção de Ervas:** Permite a seleção de 2 a 7 ervas para combinação.
- **Análise de Compatibilidade:** Verifica conflitos entre as regências planetárias das ervas selecionadas.
- **Detalhamento de Conflitos:** Apresenta os motivos dos conflitos, seus possíveis efeitos e sugestões de neutralização.
- **Balanço de Temperaturas:** Mostra a distribuição de temperaturas (quente, morna, fria) na combinação.
- **Usos Mágickos Combinados:** Lista todos os usos mágickos possíveis com as ervas selecionadas.
- **Dicas de Banhos:** Oferece orientações sobre o uso de banhos quentes, mornos e frios.
- **Expansão com Ervas Brasileiras:** Inclui uma vasta gama de ervas tradicionais brasileiras, com suas propriedades e classificações.

## Como Usar

1. Abra o arquivo `combinador_ervas_expandido.html` em seu navegador.
2. Selecione a quantidade de ervas que deseja combinar.
3. Escolha as ervas nos menus suspensos.
4. Clique no botão "Analisar Combinação".
5. O resultado será exibido abaixo, com todas as informações sobre a combinação.

## Como Contribuir

Este é um projeto de código aberto e contribuições são bem-vindas. Para contribuir, siga os seguintes passos:

1. Faça um fork deste repositório.
2. Crie uma nova branch para sua feature (`git checkout -b feature/nova-erva`).
3. Adicione a nova erva ao objeto `ervas` no arquivo `combinador_ervas_expandido.html`, seguindo o formato existente.
4. Certifique-se de que a nova erva tenha as propriedades `planeta`, `temperatura`, `usos`, `genero` e `nova: true`.
5. Faça o commit de suas alterações (`git commit -m 'Adiciona nova erva: Nome da Erva'`).
6. Faça o push para a branch (`git push origin feature/nova-erva`).
7. Abra um Pull Request.

## Estrutura do Código

O código está contido em um único arquivo HTML (`combinador_ervas_expandido.html`) e é dividido em três partes:

- **HTML:** A estrutura da página, com os seletores e a área de resultado.
- **CSS:** O estilo da página, com as cores, fontes e layout.
- **JavaScript:** A lógica do combinador, com os dados das ervas, as regras de conflito e a função de análise.

### Objeto `ervas`

O objeto `ervas` contém todas as informações sobre cada erva, no seguinte formato:

```javascript
"Nome da Erva": {
  planeta: "Planeta Regente",
  temperatura: "quente" | "morna" | "fria",
  usos: ["Uso 1", "Uso 2", ...],
  genero: "masculino" | "feminino",
  nova: true // Opcional, para destacar novas ervas
}
```

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

