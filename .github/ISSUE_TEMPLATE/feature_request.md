---
name: ✨ Solicitar novo recurso
about: Sugira uma ideia para este projeto
labels: 'enhancement'
---

body:
- type: markdown
  attributes:
    value: |
      **Orientações:**
      - Verifique nas [issues existentes](https://github.com/fct-coders/hacktoberfest-2021-presencas/issues?q=is%3Aissue) se este recurso já não foi solicitado.
      - Se você quiser fazer uma pergunta, por favor, use as [discussões](https://github.com/fct-coders/hacktoberfest-2021-presencas/discussions).
      - Escreva um título descritivo. Evite títulos genéricos ou vagos, tais como "Quero algo novo" ou "Achei isso legal".
      - Mantenha sua issue centrada em um único recurso. Se você tiver várias solicitações, por favor, crie issues separadas para cada uma delas.
      - Forneça o máximo de contexto possível. Inclua capturas de tela, gravações de tela, links, referências ou qualquer outra coisa que você possa considerar relevante.

- type: textarea
  attributes:
    label: Detalhes
    description: Explicação clara e completa do recurso e seus propósitos.
    placeholder: Eu gostaria que a parte X do site tenha o recurso Y, porque Z.
  validations:
    required: true
