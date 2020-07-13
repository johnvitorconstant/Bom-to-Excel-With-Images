# Bom-to-Excel-With-Images
INTRODUÇÃO
Um dos maiores desafios para quem faz desenvolve projetos de montagens com muitas peças é o gerenciamento e rastreamento das peças na manufatura. Uma das formas mais efetivas de fazer esse rastreamento é através de checklist e BOM (Bill of Materials).
O SolidWorks¹ possui uma ferramenta interna que gera tabela de montagens e peças muito eficiente, porém essa lista peca em um simples detalhe: ausência de uma “imagem” da peça na tabela.
Navegando na Internet acabei me deparando com uma macro muito boa para gerar essas tabelas com imagens (acredite em mim, essas imagens fazem TODA a diferença), essa macro pode ser encontrada em https://bluebyte.biz/macros/export-solidworks-bom-to-excel-with-thumbnail-preview-solidworks-macro/.
Modifiquei a macro do site citado anteriormente resolvendo alguns bugs e adicionando outras funções. A Versão mais recente da macro você baixa no link a seguir:
https://drive.google.com/open?id=16EE3iDsiIs8YIlNGKlH6rFHGnkT1Rm0E

tl:dr
O funcionamento da macro é bem simples, basta seguir esses passos:
1º Faça o download da macro em https://drive.google.com/open?id=16EE3iDsiIs8YIlNGKlH6rFHGnkT1Rm0E
2º Estar com a montagem aberta
3º Resolver toda a montagem
4º Gerar uma lista de materiais e/ou selecionar alguma já existente
5º Rodar a macro

Dicas
A imagem gerada será salva com as configurações do “salvar como png” portanto se quiser bordas mais definidas, aumente a resolução não opções, se quiser bordas mais espeças, diminua a resoluçãoListas de materiais são ferramentas poderosas quando utilizadas de forma correta, nesse outro artigo eu ensino como criar propriedades personalizadas no SolidWorks de forma rápida e utilizar essas propriedades para gerar uma lista de material completa

Notas
Lista de modificações realizadas pelo autor deste artigo com relação à macro original do blubyte.biz:

A macro original não lida muito bem com o local em que as imagens são salvas, modifiquei para que estas sejam salvas junto ao arquivo original, no formato png (preservando a transparência)
Ao salvar a imagem em um local fixo, o problema de incompetibilidade com o salvar do Excel foi resolvido, uma vez que o Excel não lida muito bem com arquivos temporários.
Adicionei opções ao método que as peças são exportadas e ampliei o escopo para funcionar tanto em tabelas de partes, nível superior, e inerentes.
Agora a macro gera um relatório com a quantidade de peças e o tempo de processamento total e de cada peça
Observações
¹A partir do Solidworks 2019 essa função foi implementada nativamente no software, como pode ser visto em https://www.javelin-tech.com/blog/2018/09/solidworks-bom-component-preview/