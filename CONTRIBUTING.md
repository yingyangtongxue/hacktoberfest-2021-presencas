## Guia de contribuição

### Deseja adicionar sua presença no evento?

Para adicionar sua presença neste evento, siga os simples passos a seguir:

1. Faça um "fork" do repositório.
2. Clone o seu fork em sua máquina local:

```bash
git clone https://github.com/USER/hacktoberfest-presencas.git
```

3. Abra o arquivo `data/_contributors.json` em algum editor de texto.

4. Siga o modelo (template) para adicionar a sua presença:

```json
{
    "username": "daenerystargaryem",
    "about": "Queen of Meereen, Khaleesi of the Great Grass Sea, Mother of Dragons, The Unburnt, Breaker of Chains, Television, Queen of the Andals and the First Men, Protector of the Seven Kingdoms, Lady of Dragonstone",
    "year": "2005",
    "languages": ["High-Valirian", "English"]
}
```
Onde…  
`username` é o seu nome de usuário no GitHub  
`about` é uma frase que você gosta ou que te descreve  
`year` é o seu ano de ingresso no curso  
`languages` são as linguagens de programação que você sabe

5. Certifique-se de que tudo esteja OK. Teste o site diretamente pelo navegador.
6. Navegue até o diretório que você clonou através do seu git CLI (no terminal).
7. Crie uma branch para a sua alteração:

```bash
git checkout -b add-contributor
```

8. Adicione as mudanças realizadas:

```bash
git add data/_contributors.json # OU 'git add -u' OU 'git add .'
```

9. E realize o commit:

```bash
git commit -m "feat: add {username} contributor"
```

Onde `{username}` é o seu nome de usuário no GitHub.

10. Realize o envio dessas mudanças para o repositório remoto:

```bash
git push origin add-contributor
```

11. Crie sua pull request e aguarde a aprovação. 🎉
