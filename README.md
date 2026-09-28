# Linfozen

Página estática pronta para a Vercel. O arquivo publicado é `public/index.html`.

## Deploy

1. Na Vercel, escolha Add New > Project e importe `flavialimahot5-bot/vslsarivs`.
2. Mantenha a Root Directory na raiz do repositório.
3. Framework: Other. Sem comando de build ou instalação. Output Directory: public.
4. Clique em Deploy. O arquivo `vercel.json` já define essas configurações.

Não são necessárias variáveis de ambiente.

Qualquer caminho diferente de `/` redireciona para a página principal com HTTP 307. A raiz fica fora da regra para evitar loop. Os recursos da página estão incorporados no HTML ou hospedados externamente.

## Vídeo e ofertas

- Player VTurb: `6ab9da13f94ad8ef5748178b`.
- Ofertas liberadas na posição 1675 segundos (27:55) do vídeo.
- Sem liberação por tempo de página aberta. Se o tempo do player não estiver acessível, as ofertas permanecem ocultas.
- Imagens incorporadas no HTML; fontes e player carregados de serviços externos.
- Os links de checkout existentes foram preservados.

Após publicar, confira a reprodução no domínio final e a liberação das ofertas. Restrições de domínio configuradas na conta VTurb precisam permitir esse domínio.

Para editar a página, altere `public/index.html` e envie um novo commit.
