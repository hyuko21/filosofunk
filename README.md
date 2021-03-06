# Filosofunk [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
Lindas frases para aquecer os corações

![Screenshot](img/screenshot.PNG?raw=true "Screenshot")

Para ver o projeto rodando: http://filosofunk.com.br/

## O que é isto?
Projeto feito nas horas vagas sem auxílio de bibliotecas e frameworks, utilizando apenas Vanilla JS, HTML e CSS, com o intuito de juntar frases engraçadas, divertidas, filosóficas ou criativas de músicas de funk.

## Como sugerir novas frases?
As frases estão armazenadas no arquivo [poesias.json](https://github.com/IgorRozani/filosofunk/blob/master/poesias.json), adicione as novas frases ao final do arquivo, utilizando a seguinte estrutura: 

```JSON
{
        "estrofe": "Um pente é pente",
        "poesia": "É o pente",
        "poeta": "Os Hawaianos",
        "id": "dEh3dJORNU4",
        "start": "36"
}
```
Os campos são os seguintes:
- Estrofe: trecho da música
- Poesia: nome da música
- Poeta: nome do cantor(a) ou grupo. Caso seja mais de um cantor(a), utilizar o & entre os nomes. Exemplo: Pikeno & Menor
- id: id do vídeo no youtube
- start: tempo do vídeo que ocorre pela primeira vez o trecho

## Como sugerir mudanças?
O projeto possui apenas uma regra: não é permitido utilizar frameworks e/ou bibliotecas, apenas Vanilla JS.

## Agradecimentos
Muito obrigado pela ajuda de Astolfo, José Francisco, Vitor Hugo, Giancarlo Rocha e aos contribuidores.
