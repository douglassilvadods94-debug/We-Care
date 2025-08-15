# Copilot Instructions for DevClub CSS Project

## Visão Geral
Este projeto é uma demonstração simples de uso de CSS para estilização de elementos HTML. Ele consiste em um arquivo `Index.html` e um arquivo de estilos `style.css`. Não há dependências externas, scripts ou integrações complexas.

## Estrutura do Projeto
- `Index.html`: Contém a estrutura básica da página, com três `<div>`s usando classes CSS para estilização.
- `style.css`: Define estilos para as classes `.box`, `.box-2` e `.box-3`.

## Padrões e Convenções
- Classes CSS seguem o padrão `.box`, `.box-2`, `.box-3` para facilitar a reutilização e modificação de estilos.
- O arquivo HTML referencia o CSS via `<link rel="stylesheet" href="./style.css">`.
- O projeto utiliza apenas HTML e CSS, sem JavaScript ou frameworks.
- O idioma padrão do HTML é `pt-br`.

## Fluxos de Trabalho
- Para visualizar alterações, basta abrir `Index.html` em um navegador.
- Não há processos de build, testes automatizados ou comandos especiais.
- Modificações em `style.css` refletem imediatamente na renderização do HTML.

## Exemplos de Padrões
```html
<div class="box">Minha Div-1</div>
<div class="box box-2">Minha Div-2</div>
<div class="box box-3">Minha Div-3</div>
```
```css
.box { background: #e0047d; }
.box-2 { background: #e9dc24; }
.box-3 { background: #2902a9; }
```

## Recomendações para Agentes
- Mantenha a simplicidade: siga o padrão de classes já existente.
- Evite adicionar dependências externas ou scripts sem necessidade.
- Documente novas classes ou padrões diretamente no CSS.
- Use nomes de classes descritivos e consistentes.

## Arquivos-Chave
- `Index.html`
- `style.css`

Seções incompletas ou dúvidas sobre padrões podem ser revisadas conforme o projeto evolui. Solicite feedback ao usuário para ajustes específicos.
