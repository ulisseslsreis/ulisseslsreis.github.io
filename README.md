# Site pessoal de Ulisses Reis

Repositório do site pessoal do **Prof. Dr. Ulisses Reis** (UFERSA), construído com [Quarto](https://quarto.org) e hospedado no GitHub Pages.

O site reúne pesquisas, projetos de dados, apresentações e materiais de ensino produzidos na área de direito constitucional, com foco em métodos empíricos aplicados ao estudo do Supremo Tribunal Federal. Esta é uma versão piloto. As seções serão preenchidas e atualizadas aos poucos.

## Acesso ao site

[Clique aqui para acessar o site](https://ulisseslsreis.github.io/)

## Seções

- **Início**: apresentação, foto e links para perfis acadêmicos e redes sociais
- **Pesquisa**: artigos, livros e projetos de pesquisa (em construção)
- **Projetos**: bases de dados, scripts e aplicativos, como o [Atlas Constitucional](https://github.com/ulisseslsreis/atlas_constitucional_2026) (em construção)
- **Apresentações**: slides de palestras, cursos e eventos (em construção)
- **Ensino**: disciplinas e materiais didáticos (em construção)

## Atualizações

O site é atualizado conforme novos materiais são produzidos. Para publicar uma nova versão, basta editar os arquivos `.qmd`, renderizar o site e enviar as mudanças ao GitHub:

```bash
quarto render
git add .
git commit -m "Descreva a atualização"
git push
```

O GitHub Pages publica automaticamente o conteúdo da pasta `docs/` do ramo `main`.

## Visual

O visual se inspira nas telas de menu dos RPGs. A navegação fica num painel à esquerda, e cada item mostra um ícone quando o cursor passa sobre ele. São a seta (Início), espada (Pesquisa), livro (Projetos), pergaminho (Apresentações) e cajado (Ensino). As setas ↑ e ↓ do teclado também percorrem o menu.

O site tem tema claro e tema escuro. Na primeira visita ele segue o tema do sistema de quem visita. O botão abaixo do menu troca o tema, e a escolha fica salva no navegador. As cores e o layout estão em `estilos.css`.

## Reprodução local

**Requisito:** [Quarto](https://quarto.org/docs/get-started/) (≥ 1.4).

Para visualizar o site no computador enquanto edita:

```bash
quarto preview
```

## Estrutura do projeto

```
site_pessoal/
├── _quarto.yml           # Configuração do site
├── index.qmd             # Página inicial (ficha e apresentação)
├── pesquisa.qmd          # Seção Pesquisa
├── projetos.qmd          # Seção Projetos
├── apresentacoes.qmd     # Seção Apresentações
├── ensino.qmd            # Seção Ensino
├── estilos.css           # Cores dos temas claro e escuro, tipografia e layout
├── parciais/
│   ├── cabecalho.html    # Fontes, ícones e aplicação do tema salvo
│   ├── menu.html         # Painel de menu com os ícones de cada seção
│   └── rodape.html       # Rodapé e scripts do menu e da troca de tema
├── imagens/              # Foto e demais imagens
└── docs/                 # Site renderizado, publicado pelo GitHub Pages
```

## Agradecimentos

Os ícones acadêmicos vêm do [Academicons](https://jpswalsh.github.io/academicons/), os demais do [Bootstrap Icons](https://icons.getbootstrap.com/) e as fontes ([Spline Sans](https://fonts.google.com/specimen/Spline+Sans) e [Spline Sans Mono](https://fonts.google.com/specimen/Spline+Sans+Mono)) do Google Fonts. Os ícones do menu foram desenhados para este site.

## Licença

O código deste repositório está licenciado sob a [MIT License](LICENSE). Os textos e a fotografia do autor não estão cobertos pela licença e não devem ser reutilizados sem autorização.

## Autor

**Ulisses Levy Silvério dos Reis**  
Professor do Curso de Bacharelado e do Programa de Pós-Graduação em Direito da UFERSA

[ORCID](https://orcid.org/0000-0003-1476-416X) | [Lattes](https://lattes.cnpq.br/5041818002534490) | [Google Scholar](https://scholar.google.com/citations?user=6zJErcYAAAAJ&hl=pt-BR) | [ResearchGate](https://www.researchgate.net/profile/Ulisses-Reis-2) | [Academia.edu](https://ufersa.academia.edu/UlissesReis) | [GitHub](https://github.com/ulisseslsreis) | [LinkedIn](https://www.linkedin.com/in/ulisses-reis-797919247/) | [Substack](https://substack.com/@ulissesreis) | [Bluesky](https://bsky.app/profile/ulissesreis.bsky.social) | [Instagram](https://www.instagram.com/ulisseslsreis/)
