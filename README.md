# PetJunior — Site institucional

> **Acesse o site publicado:** [https://juniorbrito777.github.io/site-petjunior-html-css/](https://juniorbrito777.github.io/site-petjunior-html-css/)

Site institucional estático para um pet shop fictício, desenvolvido para apresentar a marca, informações sobre o negócio, uma galeria de imagens e formas de acesso à localização e ao contato.

## Visão geral

O projeto utiliza HTML semântico para estruturar o conteúdo e CSS nativo para o layout e a apresentação visual. Não requer framework, bibliotecas JavaScript, processo de compilação ou instalação de dependências: pode ser executado diretamente em um navegador e publicado como site estático no GitHub Pages.

## Funcionalidades

- Navegação entre as seções da página por links internos.
- Seção de destaque com imagem definida no CSS.
- Apresentação institucional do PetJunior.
- Galeria de imagens com carregamento adiado (`loading="lazy"`).
- Link externo para abrir a localização no Google Maps.
- Formulário de contato com campos para nome, e-mail e mensagem.
- Ajustes de layout para telas estreitas e navegação com rolagem suave.
- Metadados básicos da página e textos alternativos nas imagens.

> **Nota sobre o formulário:** os campos e o botão estão presentes na interface, mas o projeto não inclui backend nem serviço de envio. As mensagens não são transmitidas ou armazenadas.

## Tecnologias

- **HTML5:** estrutura semântica, navegação e formulário.
- **CSS3:** layout, tipografia, cores, efeitos visuais e media query para telas de até 640 px.
- **GitHub Pages:** hospedagem estática do site.

## Estrutura de arquivos

```text
site-petjunior-html-css/
├── index.html       # Página principal
├── css/
│   └── style.css    # Estilos e regras responsivas
└── img/
    ├── 1.jpg        # Imagens da galeria
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    ├── 6.jpg
    ├── hero.jpg     # Imagem de destaque usada no CSS
    └── hero.webp    # Imagem adicional
```

## Executar localmente

Não é necessário instalar dependências.

1. Clone o repositório:

   ```bash
   git clone https://github.com/juniorbrito777/site-petjunior-html-css.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd site-petjunior-html-css
   ```

3. Abra `index.html` diretamente no navegador. Como alternativa, use a extensão Live Server no VS Code para servir os arquivos durante o desenvolvimento.

## Publicação

O site está hospedado pelo GitHub Pages no endereço indicado no início deste README. Os caminhos para folhas de estilo e imagens são relativos ao projeto, compatíveis com a publicação em um subdiretório do domínio `github.io`.

## Desenvolvedor

**Junior Brito**

- GitHub: [juniorbrito777](https://github.com/juniorbrito777)
- LinkedIn: [perfil de Junior Brito](https://www.linkedin.com/in/junior-brito-8787383b3/)

---

Projeto acadêmico para estudo e prática de HTML e CSS.
