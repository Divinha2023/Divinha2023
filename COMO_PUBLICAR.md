# Como publicar este projeto no GitHub

Este projeto foi preparado para ser usado no reposit&oacute;rio especial do seu perfil:

```txt
Divinha2023/Divinha2023
```

Quando esse reposit&oacute;rio existe e possui um `README.md` na raiz, o GitHub mostra esse conte&uacute;do diretamente no seu perfil.

---

## 1. Crie o reposit&oacute;rio correto

1. Acesse: https://github.com/new
2. Em **Repository name**, escreva exatamente:

```txt
Divinha2023
```

3. Marque como **Public**.
4. N&atilde;o precisa adicionar README pelo site, porque este projeto j&aacute; tem um.
5. Clique em **Create repository**.

---

## 2. Envie os arquivos deste projeto

Voc&ecirc; precisa subir esta estrutura completa:

```txt
README.md
COMO_PUBLICAR.md
assets/
  profile-header.svg
  profile-footer.svg
.github/
  workflows/
    contribution-map.yml
```

Se for pelo site do GitHub:

1. Abra o reposit&oacute;rio `Divinha2023/Divinha2023`.
2. Clique em **Add file**.
3. Clique em **Upload files**.
4. Arraste todos os arquivos e pastas do projeto.
5. Clique em **Commit changes**.

Se for pelo terminal:

```bash
git init
git add .
git commit -m "Cria README profissional do perfil"
git branch -M main
git remote add origin https://github.com/Divinha2023/Divinha2023.git
git push -u origin main
```

---

## 3. Ative o GitHub Actions

O mapa de contribui&ccedil;&otilde;es usa um workflow do GitHub Actions para gerar os arquivos SVG automaticamente.

Depois de subir o projeto:

1. Entre no reposit&oacute;rio no GitHub.
2. Clique na aba **Actions**.
3. Se aparecer uma mensagem pedindo permiss&atilde;o, clique em **I understand my workflows, go ahead and enable them**.
4. Clique no workflow **Generate contribution map**.
5. Clique em **Run workflow**.
6. Confirme em **Run workflow**.

Quando terminar, o GitHub criar&aacute; um branch chamado:

```txt
output
```

Esse branch conter&aacute; os arquivos:

```txt
github-contribution-grid-snake.svg
github-contribution-grid-snake-dark.svg
```

---

## 4. Configure permiss&atilde;o de escrita para o workflow

Se o workflow falhar com erro de permiss&atilde;o:

1. Entre no reposit&oacute;rio.
2. Clique em **Settings**.
3. Clique em **Actions**.
4. Clique em **General**.
5. Procure **Workflow permissions**.
6. Marque:

```txt
Read and write permissions
```

7. Clique em **Save**.
8. Volte em **Actions** e rode o workflow novamente.

---

## 5. Personalize seus contatos

No `README.md`, procure esta parte:

```md
[![LinkedIn](...)](https://www.linkedin.com/)
[![Email](...)](mailto:seu-email@exemplo.com)
```

Troque pelo seu LinkedIn e seu email real.

---

## 6. Veja o resultado final

Depois de publicar, acesse:

```txt
https://github.com/Divinha2023
```

Seu perfil deve mostrar:

- Header roxo profissional.
- Apresenta&ccedil;&atilde;o pessoal.
- Stack de tecnologias.
- Projetos em destaque.
- Estat&iacute;sticas do GitHub.
- Mapa de contribui&ccedil;&otilde;es.
- Contatos.
