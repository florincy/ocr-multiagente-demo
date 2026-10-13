# Demonstração de OCR com revisão multiagente

[Reproduzir a demonstração](https://florincy.github.io/ocr-multiagente-demo/)

Vídeo de 25,5 segundos, H.264, 1080 × 1080, sem áudio. A caligrafia do campo numérico é original; os dados ao redor estão ocultos. A interface reconstitui leituras registradas, incluindo a revisão humana de 25,1 °C. Esta apresentação não é uma execução ao vivo nem uma medição de precisão.

## Conteúdo publicado

- `index.html`: página estática com controles de reprodução.
- `demonstracao.mp4`: vídeo final protegido.
- `poster.jpg`: imagem final protegida.
- `checksums.json`: hashes dos arquivos de mídia.

Não inclui PDFs, documentos empresariais completos, conjuntos de treinamento ou arquivos do projeto privado.

## Reproduzir localmente

Clone este repositório e, na pasta clonada, execute:

```sh
python -m http.server 8080
```

Abra http://127.0.0.1:8080/. A página não usa serviços externos nem envia dados.
