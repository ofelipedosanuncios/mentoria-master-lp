# Landing Page | Mentoria Master

Landing page da Mentoria Master, de Pamela Neto Consultoria Ambiental.

Versao em preview para aprovacao. Ainda nao e a versao publicada no dominio definitivo.

## Como rodar

Pagina estatica, sem build e sem dependencia. Abra o `index.html` no navegador ou
suba um servidor estatico:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Estrutura

```
index.html        pagina completa (HTML, CSS e JS em arquivo unico)
assets/img/       imagens usadas na pagina
```

## Estado

O formulario de aplicacao e front-end apenas: valida os campos, navega entre as
7 telas e mostra a tela de confirmacao, mas ainda nao grava nem envia as respostas.
A integracao entra na etapa de desenvolvimento.

## Publicacao

A pagina sobe como arquivo estatico. Basta enviar `index.html` e a pasta `assets/`
para a raiz do dominio.

Antes de publicar no dominio definitivo, remover a meta `robots noindex` do topo
do `index.html`.

---

Desenvolvimento: Felipe | 4R Midia
