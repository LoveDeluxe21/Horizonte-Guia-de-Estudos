# Horizonte — Guia de Estudos

Site estático para explorar cursos e materiais de estudo. Não precisa de servidor, compilação ou instalação de pacotes.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie **o conteúdo desta pasta** para a raiz do repositório. O `index.html` deve ficar diretamente na raiz, ao lado dos demais arquivos.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha a branch `main` e a pasta `/(root)`, e salve.
5. Aguarde o GitHub Pages publicar o endereço mostrado nessa página.

## Arquivos do site

- `index.html` — página inicial do Horizonte.
- `horizonte.html` — cópia de acesso direto ao Guia de Estudos.
- `material-de-estudo.html` — página separada de materiais para o Enem.
- `horizonte-logo.jpg` — logo usada pelas páginas.
- `Material teórico - porcentagem.pdf` e `Caderno de questões - porcentagem.pdf` — materiais de Matemática.
- `Industria cultural - questões.pdf` — questões de Sociologia.

Mantenha os arquivos juntos na raiz publicada: as páginas usam caminhos relativos para abrir logo, PDFs e a outra página do site. Os arquivos PDF abrem em uma nova aba do navegador.

O site usa HTML, CSS e JavaScript no próprio arquivo. As fontes DM Sans e Manrope são carregadas do Google Fonts quando há conexão; se estiver offline, fontes alternativas do dispositivo serão usadas.
