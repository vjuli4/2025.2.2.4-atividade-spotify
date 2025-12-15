# 2025.2.2.4-atividade-spotify
atividade avaliativa de reprodução de UI Web a partir de imagem

## Sumário
1. [Objetivo](#objetivo)
2. [Protótipos](#protótipos)
3. [Checklist de Implementação](#checklist-de-implementação)
   - [Preparação](#preparação)
   - [Estrutura HTML](#estrutura-html)
   - [Estilização CSS3 Mobile First](#estilização-css3-mobile-first)
   - [Responsividade](#responsividade)
   - [Finalização](#finalização)

## Objetivo
Reproduzir a interface de usuário do Spotify utilizando HTML5 e CSS3 externo com abordagem mobile-first, baseando-se nos protótipos fornecidos.

## Protótipos
Os protótipos de referência estão disponíveis no diretório `prototipos/`:
- `spotify-mobile.png` - Design para dispositivos móveis
- `spotify-desktop.png` - Design para desktop

## Checklist de Implementação

### Preparação
- [ ] Analisar os protótipos mobile e desktop
- [ ] Identificar os componentes principais da interface
- [ ] Planejar a estrutura semântica do HTML
- [ ] Definir breakpoints para responsividade

### Estrutura HTML
- [ ] Criar arquivo `index.html` na raiz do projeto
- [ ] Configurar a estrutura básica HTML5:
  - [ ] Adicionar `<!DOCTYPE html>`
  - [ ] Configurar tag `<html>` com atributo `lang="pt-BR"`
  - [ ] Criar seção `<head>` com:
    - [ ] Meta charset UTF-8
    - [ ] Meta viewport para responsividade
    - [ ] Tag `<title>` apropriada
    - [ ] Link para arquivo CSS externo
- [ ] Estruturar o `<body>` com elementos semânticos:
  - [ ] Header (cabeçalho/navegação)
  - [ ] Main (conteúdo principal)
  - [ ] Footer (rodapé)
- [ ] Adicionar conteúdo textual e imagens conforme protótipo mobile
- [ ] Validar HTML em https://validator.w3.org/

### Estilização CSS3 Mobile First
- [ ] Criar arquivo `style.css` (recomendado: criar pasta `css/` e salvar como `css/style.css`)
- [ ] Configurar reset/normalize CSS:
  - [ ] Remover margens e paddings padrão
  - [ ] Definir box-sizing como border-box
- [ ] Implementar estilos base (mobile first):
  - [ ] Tipografia (fontes, tamanhos, cores)
  - [ ] Cores de fundo
  - [ ] Espaçamentos (margins e paddings)
  - [ ] Layout flexbox ou grid
- [ ] Estilizar componentes específicos:
  - [ ] Barra de navegação/header
  - [ ] Cards ou seções de conteúdo
  - [ ] Botões e elementos interativos
  - [ ] Imagens e ícones
  - [ ] Footer
- [ ] Aplicar efeitos CSS3:
  - [ ] Transições
  - [ ] Sombras (box-shadow)
  - [ ] Bordas arredondadas (border-radius)
  - [ ] Gradientes (se aplicável)

### Responsividade
- [ ] Implementar media queries para tablet (min-width: 768px):
  - [ ] Ajustar layouts
  - [ ] Modificar tamanhos de fonte
  - [ ] Reorganizar elementos se necessário
- [ ] Implementar media queries para desktop (min-width: 1024px):
  - [ ] Aplicar layout do protótipo desktop
  - [ ] Ajustar larguras máximas
  - [ ] Otimizar espaçamentos
- [ ] Testar em diferentes tamanhos de tela (sugestão: 320px, 768px, 1024px, 1440px) usando DevTools do navegador

### Finalização
- [ ] Testar a página em navegadores diferentes (Chrome, Firefox, Safari, Edge)
- [ ] Verificar acessibilidade básica:
  - [ ] Alt text em imagens
  - [ ] Contraste de cores adequado
  - [ ] Estrutura de headings hierárquica
- [ ] Validar CSS em https://jigsaw.w3.org/css-validator/
- [ ] Otimizar performance:
  - [ ] Comprimir imagens se necessário
  - [ ] Remover código CSS não utilizado
- [ ] Documentar decisões técnicas (se necessário)
- [ ] Fazer commit final do projeto
