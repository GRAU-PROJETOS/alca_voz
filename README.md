# AlçaVoz em HTML

Extraia a pasta do ZIP e abra index.html com dois cliques. Mantenha a pasta imagens ao lado do HTML. O site também funciona offline, inclusive os detalhes das campanhas e a animação da capa.

## Como editar o texto

Abra index.html no editor de texto de sua preferência ou use o lápis do GitHub. Pesquise por EDITE AQUI para ir direto ao menu, à capa, à coleção, a cada campanha, à seção do projeto ou ao rodapé. Substitua as frases entre as tags. Por exemplo, em <p>Lorem ipsum...</p>, mantenha <p> e </p> e troque a frase entre eles. O título da aba do navegador fica em <title>. As cores, animações e regras para celular ficam no bloco <style> no início do HTML.

## Como trocar as imagens

Cada posição tem um arquivo próprio, mesmo que todas comecem com a mesma arte.

| Posição | Arquivo |
| --- | --- |
| Capa animada | imagens/capa.jpg |
| Setembro Amarelo | imagens/setembro-amarelo.jpg |
| Outubro Rosa | imagens/outubro-rosa.jpg |
| Novembro Azul | imagens/novembro-azul.jpg |

Substitua o JPG correspondente e recarregue a página. Para usar um PNG ou WebP, coloque-o em imagens e altere o caminho em src no bloco da peça. Por exemplo, src="imagens/novembro-azul.webp". Atualize também o atributo alt com uma breve descrição da foto. O texto impresso dentro da logo faz parte da imagem.

## Publicar no GitHub Pages

1. Em github.com/new, crie um repositório para a versão HTML, por exemplo alcavoz-site. No GitHub Free, escolha Public. Assim você pode manter o projeto Streamlit no repositório anterior, inclusive se ele for privado.
2. Abra o repositório e use “uploading an existing file” ou “Add file → Upload files”. Arraste os arquivos extraídos e a pasta imagens. Confira se index.html está no primeiro nível e se aparece imagens/capa.jpg. Salve em “Commit changes”.
3. Acesse “Settings → Pages”. Em “Build and deployment”, escolha “Deploy from a branch”. Selecione a branch que recebeu os arquivos (geralmente main), a pasta /(root) e clique em “Save”.
4. Aguarde a publicação. Em “Settings → Pages”, clique em “Visit site”. Copie o endereço publicado para compartilhar com a turma ou usar no QR Code.
5. Para atualizar, edite index.html ou envie uma nova foto para imagens e confirme a alteração na mesma branch. O GitHub Pages publicará a atualização no mesmo endereço.

[Documentação do GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Tema e idioma

O site começa em português e no tema claro. A lua no canto inferior direito ativa o tema escuro. Toque no sol para voltar. No menu superior, escolha Português, Español ou English. As preferências ficam salvas no navegador quando o armazenamento local está disponível.

Em index.html, cada trecho traduzido tem o texto em português entre as tags, a versão em espanhol em data-es e a versão em inglês em data-en. As descrições das imagens ficam em alt, data-alt-es e data-alt-en. Você pode editar as três versões no próprio arquivo. Os dizeres impressos nas artes fazem parte das imagens originais.
