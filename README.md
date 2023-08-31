# Prevendo-Ocorrencia-de-Cancer
Ciência de Dados 

Sobre o conjunto de dados
As características são calculadas a partir de uma imagem digitalizada de um aspirado com agulha fina (PAAF) de uma massa mamária. Eles descrevem características dos núcleos celulares presentes na imagem.
o espaço tridimensional é aquele descrito em: [KP Bennett e OL Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

Este banco de dados também está disponível através do servidor FTP UW CS:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Também pode ser encontrado no UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Informações do atributo:

1) Número de identificação
2) Diagnóstico (M = maligno, B = benigno)
3-32)

Dez características de valor real são calculadas para cada núcleo celular:

a) raio (média das distâncias do centro aos pontos do perímetro)
b) textura (desvio padrão dos valores da escala de cinza)
c) perímetro
d) área
e) suavidade (variação local nos comprimentos do raio)
f) compacidade (perímetro ^ 2 /área - 1,0)
g) concavidade (gravidade das porções côncavas do contorno)
h) pontos côncavos (número de porções côncavas do contorno)
i) simetria
j) dimensão fractal ("aproximação da linha costeira" - 1)

A média, o erro padrão e o “pior” ou maior (média dos três
maiores valores) desses recursos foram calculados para cada imagem,
resultando em 30 recursos. Por exemplo, o campo 3 é o raio médio, o campo
13 é o raio SE, o campo 23 é o pior raio.

Todos os valores de recursos são recodificados com quatro dígitos significativos.

Valores de atributos ausentes: nenhum

Distribuição de classes: 357 benignos, 212 malignos
