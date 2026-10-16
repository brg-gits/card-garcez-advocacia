# Garcez Advocacia — cartão digital

Cartão digital estático, responsivo e institucional, criado com o logotipo oficial.

## Estrutura na raiz do repositório

- `card.html` — página com botões para WhatsApp, Instagram, Facebook, site, e-mail e Google Maps.
- `index.html` — redireciona a raiz do GitHub Pages para `card.html`.
- `contato.vcf` — contato institucional para salvar na agenda.
- `assets/logo-oficial.png` — logotipo oficial fornecido (sem redesenho).
- `assets/qr-contato.svg` — QR Code do arquivo vCard publicado no GitHub Pages.
- `.nojekyll` — desativa processamento Jekyll.

## Publicação com GitHub Pages

O repositório foi encontrado como **privado**. O GitHub Pages precisa estar disponível no plano da conta e ser configurado em **Settings > Pages** com a origem **Deploy from a branch**, branch `main`, pasta `/(root)`.

Após ativar o Pages, o endereço esperado do cartão será:

https://brg-gits.github.io/card-garcez-advocacia/card.html

O QR Code aponta para:

https://brg-gits.github.io/card-garcez-advocacia/contato.vcf

Enquanto o GitHub Pages não estiver ativo, o QR Code não pode entregar o contato.

## Migração para domínio próprio

Para publicar posteriormente no site, mover os arquivos da raiz para `https://dgarcez.com.br/contato/`, manter referências relativas e **regenerar o QR Code** para a nova URL, ou manter a URL antiga funcionando.

## Privacidade

Não há formulários, analytics, cookies ou armazenamento de dados de visitantes. A página divulga somente os contatos institucionais informados.

## QR Code de contato

O QR Code em `assets/qr-contato.svg` armazena diretamente um vCard 3.0 (nome institucional, telefone, e-mail e site). Câmeras compatíveis podem abrir a criação de contato sem acessar uma URL. O botão `Salvar contato` e o clique na imagem continuam oferecendo o `contato.vcf` completo (incluindo endereço). O QR Code não depende mais do domínio da hospedagem. A importação final requer confirmação do usuário e pode variar conforme o aplicativo de câmera.

## Identidade e contato (atualização de 16/10/2026)

- O nome exibido é **Garcez Advocacia - Dra. Danielle Rosas Garcez**.
- O vCard baixável contém endereço e foto de perfil SELO1.png incorporada em base64.
- O QR Code incorpora nome, telefone, e-mail, endereço e site em vCard 3.0; a foto não é embutida no QR Code para preservar a leitura nativa por câmeras móveis.
- A imagem SELO1.png, fornecida pelo escritório, também é a base do favicon redondo com fundo azul-escuro.
- A página card.html segue na raiz do repositório.
