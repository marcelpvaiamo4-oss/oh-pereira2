# Oh Pereira — Casa de Pasto

Site do restaurante **Oh Pereira — Casa de Pasto**, cozinha portuguesa na R. Arco do Cego 59, Lisboa.

## O que tem no site

- Apresentação da casa e da gastronomia
- Carta digital com carrinho: o cliente escolhe as quantidades e o pedido é montado e enviado pelo WhatsApp
- Experiência e galeria de fotos
- Reservas, localização e contatos

## Como funciona

Site estático em **um único arquivo** (`index.html`), com HTML, CSS e JavaScript puros. As imagens estão embutidas no próprio arquivo e as fontes vêm do Google Fonts. Não há build nem dependências para instalar.

Para ver localmente, basta abrir o `index.html` no navegador.

## Publicação

Funciona em qualquer hospedagem estática:

- **Vercel:** Add New → Project → importar este repositório → Deploy (sem configuração extra).
- **GitHub Pages:** Settings → Pages → Deploy from a branch → `main` / `(root)`.

## Onde editar

- **Número do WhatsApp do carrinho:** variável `WHATSAPP_NUMBER`, no script perto do fim do `index.html`. O mesmo número aparece também nos botões de reserva e ligar, no rodapé e nos dados estruturados (`"telephone"`) no topo do arquivo.
- **Instagram:** links para `instagram.com/ohpereira_casadepasto`.

---

Desenvolvido por **IDEAL SOLUTIONS** · [idealsolutions2011.com.br](https://idealsolutions2011.com.br)
