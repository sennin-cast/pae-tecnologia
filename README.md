# E.P.A Tecnologia — Apresentação Executiva & Portfólio

Landing page institucional e portfólio da **E.P.A Tecnologia**, desenvolvida para apresentar serviços de Engenharia de Dados, ETL & Integração de Dados e Desenvolvimento Web, além de cases, metodologia e um simulador de briefing para novos projetos.

## 🌐 Projeto

Este projeto é uma página web **100% estática**, preparada para publicação no **GitHub Pages**.

Não utiliza backend, banco de dados ou processo de build. Basta publicar o `index.html` em um repositório com o GitHub Pages habilitado.

## ✨ Principais recursos

- Layout responsivo para desktop, tablet e celular;
- Identidade visual da E.P.A Tecnologia;
- Seção de apresentação profissional;
- Posicionamento como Engenheiro de Dados & Desenvolvedor Web;
- Seção de filosofia e diferenciais;
- Portfólio com projetos reais;
- Links externos para os cases;
- Seção de metodologia de trabalho;
- Simulador interativo de briefing;
- Botão para copiar o briefing;
- Botão para enviar o briefing diretamente pelo WhatsApp;
- Botão flutuante de WhatsApp;
- WhatsApp configurado para **(21) 97945-1436**;
- SEO básico com `title`, `description`, `robots` e dados Open Graph/Twitter;
- Favicon em SVG embutido no próprio HTML;
- Dados estruturados em JSON-LD;
- Melhorias de acessibilidade com foco visível e suporte a `prefers-reduced-motion`;
- Links externos configurados com `target="_blank"` e `rel="noopener noreferrer"`;
- Imagem principal incorporada no próprio HTML, sem depender de arquivo de imagem externo.

## 📱 WhatsApp

O site utiliza o seguinte número para contato:

**(21) 97945-1436**

Formato utilizado nos links do WhatsApp:

`https://wa.me/5521979451436`

O botão do simulador também abre o WhatsApp já com o briefing do projeto preenchido na mensagem.

## 📁 Estrutura recomendada

```text
seu-repositorio/
├── index.html
└── README.md
```

O arquivo principal deve obrigatoriamente se chamar:

```text
index.html
```

Isso permite que o GitHub Pages carregue a página automaticamente como página inicial.

## 🚀 Publicação no GitHub Pages

### 1. Crie um repositório

No GitHub, crie um novo repositório para o projeto.

Exemplo:

```text
epa-tecnologia
```

### 2. Envie os arquivos

Faça upload destes arquivos:

```text
index.html
README.md
```

### 3. Ative o GitHub Pages

No repositório:

**Settings → Pages**

Em **Build and deployment**, selecione:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Depois clique em **Save**.

### 4. Acesse o site

A URL seguirá este padrão:

```text
https://SEU-USUARIO.github.io/epa-tecnologia/
```

Substitua `SEU-USUARIO` pelo seu usuário do GitHub e `epa-tecnologia` pelo nome do repositório.

## 🔗 Cases apresentados

A página possui links para os seguintes projetos:

- Maurício Gimenez — `https://mauriciogimenez.com.br`
- MR Britto Advocacia — `https://sennin-cast.github.io/mrbritto-advocacia/`
- UNA Essence — `https://sennin-cast.github.io/una-essence/`
- Risi Melo — `https://sennin-cast.github.io/risi-melo/`
- Academia Maia — `https://sennin-cast.github.io/academia-maia/`

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Tailwind CSS via CDN
- Lucide Icons
- Google Fonts
- SVG
- JSON-LD / Schema.org

## ⚡ Características técnicas

### Sem backend

O projeto não depende de:

- PHP;
- Node.js no servidor;
- banco de dados;
- API própria;
- hospedagem tradicional;
- servidor de aplicação.

O GitHub Pages é suficiente para hospedar a página.

### Imagem incorporada

A imagem principal está incorporada diretamente no HTML em formato Base64. Portanto, não é necessário criar uma pasta adicional de imagens para que a página funcione.

### WhatsApp

O contato utiliza o formato internacional:

```text
55 + DDD 21 + número 979451436
```

Resultando em:

```text
5521979451436
```

## 🔎 SEO

O `index.html` inclui:

- título otimizado;
- meta description;
- `robots`;
- `theme-color`;
- Open Graph;
- Twitter Card;
- idioma `pt-BR`;
- dados estruturados `ProfessionalService`;
- favicon.

### Canonical

O arquivo contém um espaço preparado para a URL canônica.

Depois de publicar o site, recomenda-se substituir o placeholder:

```html
https://SEU-USUARIO.github.io/SEU-REPOSITORIO/
```

pela URL definitiva do projeto.

## 📱 Responsividade

O layout foi estruturado para funcionar em:

- smartphones;
- tablets;
- notebooks;
- monitores desktop.

Também foram adicionados cuidados para navegação por teclado, foco visível e redução de animações quando essa preferência estiver habilitada no dispositivo.

## 🔐 Segurança dos links externos

Os links externos abertos em nova aba utilizam:

```html
target="_blank"
rel="noopener noreferrer"
```

Isso evita que a página de destino tenha acesso desnecessário à janela de origem.

## 📞 Contato

**E.P.A Tecnologia**

Engenharia de Dados • ETL & Integração de Dados • Desenvolvimento Web

**WhatsApp:** (21) 97945-1436

## 📄 Licença

Este projeto é um material institucional/portfólio da E.P.A Tecnologia. O conteúdo, identidade visual, textos, imagens e estrutura não devem ser reutilizados comercialmente sem autorização.

---

**E.P.A Tecnologia — Dados, tecnologia e presença digital.**
