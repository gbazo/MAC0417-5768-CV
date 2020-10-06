# EP1 – Formação da base de imagens

MAC0417/5768 - Visão e Processamento de Imagens
Gabriel Bazo
NUSP: 10277231

A base de dados a seguir é formada por um conjunto de imagens de objetos encontrados em casa (por exemplo, garfos, facas, poltronas, celulares, roupas, pets). A base de imagens seguiu as seguintes características:

    • 10 classes
    • mínimo de 3 e máximo de 10 objetos por classe
    • 3 variações de fundo por objeto
    • 4 variações de iluminação por objeto com os produtos cartesianos: {dentro de casa, fora de casa} X {de dia, de noite}
    • 3 repetições para cada situação acima

  O total de imagens coletadas foram de 1080, sendo 270 em cada variação de iluminação. Para essa tarefa foi utilizado uma única câmera, presente no smartfone Xiaomi MI A3, esta possui 48 megapixels, abertura de 1.8 e foco tipo PDAF (Phase Detection AutoFocus). Todas as imagens foram capturadas em resolução FullHD (1920x1080px), apesar da possibilidade de realizar a captura das imagens em resoluções consideravelmente superiores, essa foi determinada por alguns motivos, permitiu a homogeneidade na base de dados e o tamanho dos arquivos puderam ser reduzidos sem comprometer a qualidade necessária para as próximas etapas.
  
  No nível de software, foi utilizado a aplicação Open Camera em conjunto com o sistema Android 10. A escolha desse aplicativo se fez dado que o mesmo é gratuito e permite um leque de configurações superior ao aplicativo de fotografia nativo do aparelho.
  
  Além da base de dados não estruturada (imagens), uma base de dados estruturada foi criada com as informações e metadados de cada imagem, permitindo assim a exploração e análise por completa das informações. Duas tabelas foram criadas, a primeira, Tabela Global, consiste nas informações necessárias para endereçar cada imagem, a segunda, Tabela Detalhada, contem todas as características de cada imagem.  

## Link para o banco de imagens

https://drive.google.com/drive/folders/1dt4AzHLzmXjKoj1Knm4JLJ1qDdoQFuBo?usp=sharing

## Link para os metadados

https://drive.google.com/file/d/13yqDY7XBFOEQbQSSim4BWnlU3M3Vr6ag/view?usp=sharing

## Link para o notebook

https://drive.google.com/file/d/10FrcNRqeN8ry-kDXX-AxzXtKnBkDdX2F/view?usp=sharing
