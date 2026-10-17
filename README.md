# iSpeak!!! — uma palavra aleatória por vez

Aplicativo PWA para estudar vocabulário em inglês com transcrição fonética IPA, tradução em português e áudio de pronúncia.

## Interface
- Uma única palavra aleatória por tela.
- Botão principal de avançar/sortear outra palavra.
- Logotipo e nome no topo à esquerda.
- Alternância claro/escuro no topo à direita.
- Controles apenas com ícones, centralizados abaixo do cartão.
- Favoritos, marcação de palavras aprendidas, progresso local e atalhos de teclado.
- Layout responsivo para desktop e celular.

## Arquivos
- `index.html`: estrutura da interface
- `styles.css`: temas claro/escuro e layout responsivo
- `app.js`: sorteio, áudio, favoritos, progresso e tradução sob demanda
- `data/words.json`: catálogo com 5.000 entradas
- `manifest.webmanifest`: metadados de instalação PWA
- `sw.js`: cache dos arquivos para uso offline
- `assets/`: logotipo e ícones

## Publicar no GitHub Pages
1. Crie um repositório GitHub chamado `ispeak`.
2. Envie todos os arquivos e pastas mantendo a estrutura.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.
5. Salve e aguarde o endereço do Pages.

## Observações
O catálogo contém 5.000 entradas. Algumas traduções e transcrições fonéticas podem ser consultadas online quando não estiverem preenchidas no catálogo. A voz usa a síntese de fala do navegador/dispositivo. A primeira carga precisa de internet para obter os arquivos e eventuais traduções; os arquivos já armazenados em cache podem funcionar offline.

## Atalhos
- `Espaço`: próxima palavra aleatória
- `S`: ouvir pronúncia
- `F`: adicionar/remover favorito
