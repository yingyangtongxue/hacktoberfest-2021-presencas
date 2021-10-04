---
name: 🐞 Reportar um erro
description: Reporte algo que não está funcionando.
labels: [bug]
---

body:
- type: markdown
  attributes:
    value: |
      **Orientações:**
      - Verifique nas [issues existentes](https://github.com/fct-coders/hacktoberfest-2021-presencas/issues?q=is%3Aissue) se este bug já não foi reportado.
      - Se você quiser fazer uma pergunta ou sugestão, em vez de reportar um bug, por favor, use as [discussões](https://github.com/fct-coders/hacktoberfest-2021-presencas/discussions).
      - Escreva um título descritivo. Evite títulos genéricos ou vagos, tais como "Não está funcionando" ou "Achei um problema".
      - Mantenha sua issue centrada em um único problema. Se você tiver vários relatórios de bugs, por favor, crie issues separadas para cada um deles.
      - Forneça o máximo de contexto possível. Inclua capturas de tela, gravações de tela, links, referências ou qualquer outra coisa que você possa considerar relevante.

- type: textarea
  attributes:
    label: Detalhes
    description: Explicação clara e completa do bug.
    placeholder: Vi que na parte X que o item Y se comporta de maneira Z, mas deveria comportar-se de maneira α.
  validations:
    required: true
