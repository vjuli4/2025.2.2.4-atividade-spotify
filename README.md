# Atividade Spotify (2025.2.2.4)
Atividade avaliativa de reprodução de UI Web a partir de imagem

## Sumário
1. [Objetivo](#objetivo)
2. [Protótipos](#protótipos)
3. [Checklist de Implementação](#checklist-de-implementação)
   - [Preparação](#preparação)
   - [Estrutura HTML](#estrutura-html)
   - [Estilização CSS3 Mobile First](#estilização-css3-mobile-first)
   - [Responsividade](#responsividade)
   - [Finalização](#finalização)

---

## Objetivo
Reproduzir a interface de usuário do Spotify utilizando HTML5 e CSS3 externo com abordagem mobile-first, baseando-se nos protótipos fornecidos.

## Protótipos
Os protótipos de referência estão disponíveis no diretório `prototipos/`:
- `spotify-mobile.png` - [Design para dispositivos móveis](prototipos/spotify-mobile.png)
- `spotify-desktop.png` - [Design para desktop](prototipos/spotify-desktop.png)

---

## Checklist de Implementação

---

### Preparação
- [x] Analisar os protótipos mobile e desktop
- [x] Identificar os componentes principais da interface
- [x] Planejar a estrutura semântica do HTML
- [x] Definir breakpoints para responsividade

---

### Estrutura HTML
- [x] Criar arquivo `index.html` na raiz do projeto
- [x] Configurar a estrutura básica HTML5:
  - [x] Adicionar `<!DOCTYPE html>`
  - [x] Configurar tag `<html>` com atributo `lang="pt-BR"`
  - [x] Criar seção `<head>` com:
    - [x] Meta charset UTF-8
    - [x] Meta viewport para responsividade
    - [x] Tag `<title>` apropriada
    - [x] Link para arquivo CSS externo
- [x] Estruturar o `<body>` com elementos semânticos:
  - [x] Header (cabeçalho/navegação)
  - [x] Main (conteúdo principal)
  - [x] Footer (rodapé)
- [x] Adicionar conteúdo textual e imagens conforme protótipo mobile

---

### Estilização CSS3 Mobile First
- [x] Criar arquivo `spotify.css` (recomendado: criar pasta `css/` e salvar como `css/spotify.css`)
- [x] Configurar reset/normalize CSS:
  - [x] Remover margens e paddings padrão
  - [x] Definir box-sizing como border-box
- [x] Implementar estilos base (mobile first):
  - [x] Tipografia (fontes, tamanhos, cores)
  - [x] Cores de fundo
  - [x] Espaçamentos (margins e paddings)
  - [x] Layout flexbox ou grid
- [x] Estilizar componentes específicos:
  - [x] Barra de navegação/header
  - [x] Cards ou seções de conteúdo
  - [x] Botões e elementos interativos
  - [x] Imagens e ícones
  - [x] Footer
- [x] Aplicar efeitos CSS3:
  - [x] Transições
  - [x] Sombras (box-shadow)
  - [x] Bordas arredondadas (border-radius)
  - [x] Gradientes (se aplicável)

---

### Responsividade
- [x] Implementar media queries para tablet (min-width: 768px):
  - [x] Ajustar layouts
  - [x] Modificar tamanhos de fonte
  - [x] Reorganizar elementos se necessário
- [x] Implementar media queries para desktop (min-width: 1024px):
  - [x] Aplicar layout do protótipo desktop
  - [x] Ajustar larguras máximas
  - [x] Otimizar espaçamentos
- [x] Testar em diferentes tamanhos de tela (sugestão: 320px, 768px, 1024px, 1440px) usando DevTools do navegador

---

### Finalização
- [x] Testar a página em navegadores diferentes (Chrome, Firefox, Safari, Edge)
- [x] Verificar acessibilidade básica:
  - [x] Alt text em imagens
  - [x] Contraste de cores adequado
  - [x] Estrutura de headings hierárquica
- [x] Validar CSS em https://jigsaw.w3.org/css-validator/
- [x] Otimizar performance:
  - [x] Comprimir imagens se necessário
  - [x] Remover código CSS não utilizado
     
---

### Observações

- as imagens e artistas são da conta real do professor
- pode utilizar as mesmas imagens do protótipo ou pegar suas próprias imagens
- as imagens devem ser colocadas em uma pasta, sugestão `imagens`
- deve ter mais que 3 itens em cada _carousel_
- [x] Documentar decisões técnicas (se necessário)
- [x] Fazer commit final do projeto
