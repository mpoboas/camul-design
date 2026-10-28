# Princípios do Design

Plataforma interativa da unidade curricular **CAMUL** (Conceção e Autoria Multimédia), ISEP.
Apresenta os princípios fundamentais da composição visual numa experiência guiada pelo scroll,
e introduz a equipa através de avatares em vídeo criados com o **D-ID**.

## Conteúdos

1. Regra dos terços
2. Esquerda ou direita (padrão em Z)
3. Espaço negativo e positivo
4. Contraste e tamanho (WCAG)
5. Tipografia
6. Hierarquia visual
7. Equilíbrio simétrico e assimétrico
8. Peso visual

## Estrutura

```
index.html      página única (HTML, CSS e JS sem dependências)
videos/         vídeos D-ID da equipa e imagens de capa
netlify.toml    configuração do deploy
```

## Correr localmente

Abrir `index.html` no browser, ou servir a pasta:

```
npx serve .
```

## Deploy no Netlify

Site estático, sem passo de build. Ligar o repositório no Netlify (ou arrastar a pasta para app.netlify.com/drop);
o `netlify.toml` publica a raiz do projeto.

## Equipa

| Membro | Secções |
| --- | --- |
| Miguel | Regra dos terços, Esquerda ou direita |
| Guilherme | Espaço negativo e positivo |
| Vicente | Contraste e tamanho, Tipografia |
| Manel | Hierarquia visual |
| Francisco | Equilíbrio, Peso visual |

Cada membro criou o seu próprio avatar com o D-ID.
