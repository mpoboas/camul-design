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
videos/         vídeos D-ID da equipa (membro1.mp4 … membro4.mp4)
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

Editar a constante `TEAM` no fim do `index.html` com nomes, papéis e caminhos dos vídeos.
