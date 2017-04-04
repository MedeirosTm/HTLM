# Estruturas e Tags Básicas do HTML5

O HTML5 é a nova versão padrão do HTML com novas Tags e APIs capazes de inserir facilmente um arquivo de audio ou vídeo em um site.

## Estrutura Básica

A estrutura básica do HTML5 é parecida as estrutra do XHTML e do HTML 4, contendo elementos HEAD e BODY.
```
<!DOCTYPE html>
<html lang="pt-br">
<head>

</head>
<body>

</body>
</html>
```

O DOCTYPE define qual tipo de arquivo você está escrevendo, ela é responsável por informar ao navegador qual é este tipo. É o primeiro código a ser adicionado em uma página.

Enquanto o XHTML 1.0 trazia mais informações, o DOCTYPE do HTML5 é mais simples. Segue abaixo exemplo do DOCTYPE do XHTML:

```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">´´´
```

A tag html define o início da sua página, nela podemos adicionar o *lang* definindo a linguagem (português, inglês, espanhol, etc) da página. Este atributo ajuda aos leitores de tela a ler corretamente os textos contidos na página, além dos buscadores poderem identificar o idioma e para que o navegador possa utilizar o dicionário gramatical mais correto.

No *head* ficarão informações conhecidas como *metadados*, que normalmente so globais, não aparecem na página, mas podem efetuar modificações na mesma. Aqui adicionamos o *title* para definir o título da página e mas *metas* *viewport*, *charset*, *description*, *keywords*, *cards* para as rede sociais, links de arquivos *css* e *javascript*.

Por fim, no *body* ficarão as *tags* e informações que serão mostradas ao seu usuário, interpretada pelo navegador.

## Conteúdo do HEAD

## Conteúdo do BODY

## Tags HTML e seus Significados

- DOCTYPE: define o tipo de documento
- html: define o início do documento html, todos as demais tags devem estar dentro desta tag
- head: cabeçalho onde ficar os metadados do documento, como metatgs, css e javascript
-- title: define o título do documento, mostrado na barra de títulos do navegador e como link nos mecanismos de busca
-- base: define a url base do documento
-- link: utilizado para linkar um arquivo de imagem ou css a página html
-- script: utilizado para escrever ou anexar um arquivo normalmente javascript a página
-- meta: metatags, como charset, description, viewport ou keywords
-- style: utilizada para adicionar um código css a página