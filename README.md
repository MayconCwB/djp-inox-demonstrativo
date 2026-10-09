# DJP Inox — Demonstrativo

Demonstração responsiva do aplicativo de gestão interna da DJP Artefatos de Inox.

## Acessar

https://djp-inox-demonstrativo.mayconpolako7.chatgpt.site

## Funcionalidades

- Propostas comerciais com estimativa de materiais, pagamento, garantia e espaços de assinatura.
- Contratos e recibos para visualizar, imprimir / salvar PDF e compartilhar.
- Prévias A4 em PDF na área Documentos.
- Estoque, comparação ilustrativa de fornecedores e financeiro.
- Fotos e vídeos na sessão atual.
- Manifesto e service worker para instalação como PWA.

## Executar localmente

Com Python instalado, na pasta do projeto:

```sh
python -m http.server 5173 --directory dist
```

Abra http://localhost:5173. O aplicativo usa HTML, CSS e JavaScript e não precisa de compilação.

## Estrutura

`dist/` contém o aplicativo completo, incluindo a logo e os modelos de documentos em `dist/assets/documentos/`.

## Dados da demonstração

Os dados iniciais são fictícios. Alterações são salvas somente no navegador (localStorage), e fotos / vídeos duram apenas a sessão. Não há login, servidor de dados ou consulta de preços em tempo real. Os PDFs de exemplo são estáticos. CNPJ e condições de garantia devem ser preenchidos pela empresa antes de uso real. As assinaturas são espaços no documento, sem assinatura eletrônica integrada.

A hospedagem atual permanece no endereço acima; este repositório guarda os arquivos para continuidade do projeto.
