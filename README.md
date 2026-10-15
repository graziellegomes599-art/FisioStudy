# FisioStudy — primeira versão PWA

Versão inicial responsiva e instalável do FisioStudy. Pode ser hospedada gratuitamente em um serviço estático com HTTPS (por exemplo, GitHub Pages) e adicionada à tela inicial de celulares.

## O que já existe
- Interface adaptada a celulares e computadores.
- Área de apostilas autorais de apoio, videoaulas por busca, questões com explicações, ferramentas de estudo, caderno local e referências.
- Comunidade de demonstração com criação de publicações, curtidas, comentários e exclusão **somente no navegador/dispositivo em uso**.
- Manifesto PWA e service worker para permitir instalação e cache básico offline após hospedagem HTTPS.

## Limitações importantes
- Esta versão não possui login, banco de dados online, sincronização, feed público, moderação central ou recuperação de conta.
- A comunidade é local: outros estudantes não verão as publicações. Não use dados reais de pacientes nem dados pessoais sensíveis.
- O conteúdo é material educacional introdutório; revise referências e conteúdo antes de publicar como material acadêmico oficial. Não substitui livros-texto, supervisão clínica ou diretrizes atualizadas.
- PWA não é o mesmo que aplicativo publicado na Google Play ou App Store. Publicação nas lojas exige etapas adicionais e pode envolver taxas de desenvolvedor.

## Como testar localmente
Abra `index.html` no navegador para testar a maior parte das funções. A instalação PWA e o modo offline exigem hospedagem por HTTPS ou um servidor local compatível; abrir o arquivo diretamente não ativa o service worker.

## Como publicar gratuitamente com GitHub Pages
1. Crie uma conta em GitHub.com, se ainda não tiver.
2. Crie um repositório público chamado `fisiostudy`.
3. Envie todos os arquivos e a pasta `icons` para a raiz do repositório.
4. Em **Settings → Pages**, selecione a publicação a partir da branch principal e da pasta raiz.
5. Aguarde o GitHub gerar o endereço HTTPS.
6. Abra esse endereço no celular. No Android, use o menu do navegador e escolha **Instalar app** ou **Adicionar à tela inicial**. No iPhone, abra no Safari, toque em **Compartilhar** e depois **Adicionar à Tela de Início**.

## Próxima etapa para uma comunidade real
Conectar um backend como Supabase (autenticação, banco de dados, armazenamento), configurar regras de acesso e políticas de privacidade, moderação/denúncia, exclusão de conta e proteção de conteúdo. Não coloque chaves secretas no HTML público.
