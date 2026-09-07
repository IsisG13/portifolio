# Portfólio — Ísis Souza Guimarães

Site estático (HTML/CSS/JS puro), sem build, sem dependências. Roda em qualquer host estático gratuito.

## Colocar no ar pela Vercel (grátis)

**Opção mais fácil — sem terminal:**
1. Crie uma conta em vercel.com (dá pra entrar com GitHub, Google ou e-mail).
2. No dashboard, clique em **"Add New" → "Project"**.
3. Escolha **"Deploy without Git"** / arraste a pasta `portfolio` (esta pasta, com `index.html` e `assets/`) para a área de upload.
4. Clique em **Deploy**. Em menos de um minuto você recebe uma URL tipo `seu-projeto.vercel.app`.

**Opção com GitHub (recomendada a longo prazo, fica mais fácil de atualizar depois):**
1. Crie um repositório novo no seu GitHub (ex: `portfolio`).
2. Suba o conteúdo desta pasta para o repositório (pode ser pelo próprio site do GitHub, em "Add file → Upload files").
3. Em vercel.com, clique em **"Add New" → "Project"**, conecte sua conta do GitHub e selecione o repositório.
4. Não precisa mudar nenhuma configuração de build — é um site estático. Clique em **Deploy**.
5. Toda vez que você atualizar o repositório, a Vercel republica o site sozinha.

## Editar o conteúdo

Tudo está em `index.html`. Procure pelo texto que quer mudar (ex: descrição de um projeto, e-mail, link do LinkedIn) e edite direto — não precisa saber programar para isso, é só texto dentro de tags.

- Trocar a foto: substitua o arquivo `assets/foto.jpg` por outra imagem com o mesmo nome (ou troque o nome no `<img src="...">` dentro do `index.html`).
- Adicionar um projeto novo: copie um bloco `<div class="proj">...</div>` inteiro dentro da seção `#projetos` e mude o texto.

## Depois de publicar

Atualize o campo "portfólio" do seu currículo com a URL final que a Vercel te der.
