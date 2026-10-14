# apoloravi.com.br
Apolo Ravi Tech

## Demonstração do site

Site estático responsivo, sem dependências de instalação. O logo foi recuperado das mídias fornecidas; os textos são provisórios e não representam uma importação dos posts do WordPress.

Para visualizar localmente, nesta pasta execute `python3 -m http.server 8000` e abra `http://localhost:8000`. Também é possível abrir `index.html` diretamente no navegador.

## GitHub Pages

Em Settings → Pages, selecione **GitHub Actions** como fonte. O workflow `.github/workflows/pages.yml` publica os arquivos públicos quando houver um push para `main`, ou quando executado manualmente em Actions. O endereço padrão será `https://apoloravi.github.io/apoloravi.com.br/` após a publicação bem-sucedida.

O domínio personalizado ainda não está ativado. Depois de revisar o site, configure `apoloravi.com.br` em Settings → Pages e os registros DNS conforme a documentação do GitHub Pages. Não altere o DNS antes de confirmar a hospedagem, especialmente se o domínio já serve o WordPress.

Para a migração do conteúdo, falta importar o XML do WordPress compactado, revisar links e definir redirecionamentos das URLs antigas. Nenhum PHP ou script do arquivo de uploads é executado por este site.
