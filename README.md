# ⚙️ Motor Xande – Protótipo Didático -

Este protótipo de motor elétrico visa o enriquecimento e melhoria do acervo no âmbito da iniciativa PETEE Protótipos (UFMG). Como proposta inicial, foi desenvolvido um protótipo voltado à experimentação prática em Máquinas Elétricas e Eletromagnetismo, aplicável em disciplinas e visitas de extensão. 

O modelo consiste em um motor DC funcional, puramente eletromecânico, permitindo estudar os princípios fundamentais de conversão de energia e interação de campos magnéticos.

## 📌 Objetivo do Protótipo 

* Produzir um protótipo acessível para estudantes e que diversifique o acervo do PETEE.
* Apoiar atividades de ensino e extensão com um material prático e interativo.
* Permitir a visualização física do funcionamento básico de um motor de corrente contínua (DC).

## ⚡ Princípio de Funcionamento

O funcionamento do Motor Xande baseia-se na busca contínua pelo alinhamento de campos magnéticos. Ao conectarmos os terminais a uma fonte de tensão contínua (fonte de bancada), a corrente elétrica flui pelas escovas e entra no comutador de quatro segmentos, energizando apenas uma das bobinas do rotor por vez.

O campo magnético gerado pela passagem da corrente nessa primeira bobina tenta se alinhar com o campo magnético estático do ímã permanente fixado na base. No entanto, no instante exato em que essa bobina alcançaria o alinhamento (o que faria o motor travar em equilíbrio), o próprio giro do eixo faz com que as escovas escorreguem para o próximo par de contatos no comutador.

Nesse momento crucial, a primeira bobina é desenergizada e a corrente passa a fluir pela segunda bobina. Como esta segunda bobina está montada fisicamente em um ângulo diferente (cruzada em relação à primeira), o seu campo magnético recém-criado está totalmente desalinhado em relação ao ímã da base. Isso gera um novo torque, forçando o motor a continuar girando para tentar alinhar essa nova bobina. 

Esse ciclo se repete continuamente: antes de uma bobina se alinhar, o comutador transfere a energia para a próxima, garantindo que o rotor nunca alcance o repouso e mantenha um movimento de rotação constante e mais suave.

## 🧰 Componentes e Materiais

A construção do protótipo utilizou materiais acessíveis:
* **Estrutura e Suportes:** Peças fabricadas em Impressão 3D (filamento laranja).
* **Base:** Placa retangular de MDF.
* **Estator (Campo Magnético Fixo):** 1 Ímã permanente em formato de anel posicionado no centro da base.
* **Rotor (Eletroímã):** Fio de cobre esmaltado enrolado na estrutura central impressa em 3D, formando duas bobinas independentes e cruzadas.
* **Eixo:** Haste metálica lisa central.
* **Sistema de Comutação:** 
  * *Comutador:* Cilindro no eixo dividido em **quatro segmentos** condutores (dois para cada bobina).
  * *Escovas:* Duas lâminas metálicas flexíveis fixadas nos suportes laterais, mantendo contato contínuo por atrito com o comutador.
* **Conexões Elétricas:** Fios vermelho e preto soldados aos suportes das escovas, com bornes (terminais) nas pontas para conexão com a fonte de bancada.

## 📐 Estrutura Mecânica e Montagem

* **Estator (Parte Fixa):** É composto pela base de MDF, suportes laterais em 3D, escovas metálicas e o ímã em formato de anel na parte inferior, que fornece o campo magnético de referência.
* **Rotor (Parte Móvel):** É o conjunto central rotativo composto pelo eixo de metal, o suporte em 3D com as duas bobinas de cobre e o comutador de quatro contatos acoplado à ponta do eixo.
* **Comutação/Contatos:** A energia elétrica da fonte chega pelos bornes, sobe pelas hastes de suporte e passa para as lâminas flexíveis (escovas). Essas lâminas encostam fisicamente no comutador giratório, realizando a troca mecânica de alimentação entre as duas bobinas a cada fração de giro.

## 🎥 Mídia e Funcionamento

<img width="500" alt="WhatsApp Image 2026-06-16 at 19 14 59" src="https://github.com/user-attachments/assets/ff7facc2-4a9a-46df-a0d6-8157f63e1c5e" />

<img width="500" alt="WhatsApp Image 2026-06-16 at 19 15 06" src="https://github.com/user-attachments/assets/5ec750a3-6154-4100-b722-d8d87792a8b9" />

<img width="500" alt="WhatsApp Image 2026-06-16 at 19 15 16" src="https://github.com/user-attachments/assets/10073dc3-0cee-4c40-8621-a1f15d9cefea" />

## ⚡ Especificações de Alimentação

| Parâmetro | Especificação | Observação |
| :--- | :--- | :--- |
| **Tensão de Operação** | 15 V | Utilizar fonte de bancada em Corrente Contínua (DC). |
| **Conexão** | Bornes tipo Banana | Respeitar a polaridade (Vermelho = Positivo, Preto = Negativo). |
| **Corrente** | Variável | A corrente será definida pela demanda de torque e resistência das bobinas, porém é recomendado limitar a corrente na fonte entre 500 e 700 mA, para evitar superaquecimento. |

## 🛠️ Guia de Manutenção Simples

Para garantir o bom funcionamento e a durabilidade do protótipo, realize as seguintes verificações periodicamente:

1. **Ajuste da Tensão das Escovas:** Com o uso, as lâminas metálicas laterais (escovas) podem perder a elasticidade e afastar do eixo. Dobre-as levemente para dentro com os dedos para garantir que mantenham um contato elétrico firme com o comutador, mas sem apertar demais para não frear o motor por excesso de atrito mecânico.
2. **Limpeza do Comutador:** O atrito contínuo entre as escovas e o comutador pode gerar resíduos escuros ou oxidação, prejudicando a condução elétrica. Limpe os quatro segmentos do comutador periodicamente.
3. **Inspeção das Conexões:** Verifique visualmente se os fios vermelho e preto continuam bem soldados nas bases das escovas metálicas e se os bornes de conexão não estão frouxos ou com fios rompidos.
4. **Verificação do Eixo e Atrito:** Com o motor desligado, gire o eixo central com a mão. Ele deve girar livremente, sem "agarrar".

# 🛠️ Melhorias Motor Xande

## 💡 O Problema e a Solução
O problema de perda de torque e vibrações ("trancos") no protótipo de 2 bobinas ocorre porque o comutador possui apenas duas seções. Durante a rotação, há um momento em que ambas as escovas tocam simultaneamente o isolante (plástico) entre os contatos, interrompendo totalmente a corrente do circuito.

Ao adotar um sistema de 3 bobinas e um comutador com 3 segmentos (chapinhas), esse problema é geometricamente eliminado porque os cortes do comutador estão a cada 120°, enquanto as escovas estão fixas a 180°, tornando-se impossível que as duas escovas toquem nos isolantes ao mesmo tempo. O corte entre as chapinhas deve ser estreito. Quando uma escova passa por essa fenda, sua largura faz com que ela encoste em duas chapinhas simultaneamente por uma fração de segundo. Enquanto uma escova faz "ponte" entre duas chapinhas, a escova oposta estará tocando de forma centralizada e isolada na terceira chapinha. Dessa forma, o circuito elétrico nunca é aberto e sempre há campo magnético sendo gerado para manter o motor girando suavemente.

## 🧱 Estrutura e Peças
A estrutura da base de MDF se manterá, juntamente com:
* Os mancais laterais, que são os suportes impressos em 3D que seguram o eixo.
* O eixo central, que é a vareta de metal que atravessa o motor.
* O estator, que é o ímã circular posicionado na base de madeira.
* As escovas, que são as duas hastes de metal (uma ligada ao fio vermelho positivo e outra ao fio preto negativo) continuam fixas na mesma posição, uma em cima e outra embaixo (a 180° de distância).

Modificaremos as seguintes peças:
* O Rotor, que é o suporte para as bobinas, manteremos o formato cilíndrico/disco, mas agora desenharemos 6 cavidades distribuídas uniformemente nas bordas (espaçados a cada 60 graus).
* O Comutador, que é o cilindro de contato, manteremos na vareta de metal diretamente ao lado do rotor, exatamente onde as hastes de metal (escovas) fazem o contato elétrico. Entretanto, para que as escovas de metal deslizem suavemente sem enroscar e sem dar tranco, ao invés do contato ser realizado tocando as escovas nos próprios fios de cobre das bobinas, utilizaremos fita de cobre adesiva para fazer 3 chapinhas.

## ⚙️ Passo a passo para a montagem:
Antes de começar a enrolar os fios, iremos preparar o comutador:
* Corte três tiras retangulares iguais de fita adesiva de cobre.
* Cole as três tiras ao redor do tubinho de plástico.
* Deixe um vão de plástico muito estreito entre cada chapa metálica para que elas não se toquem.
* Identifique a Chapa 1, a Chapa 2 e a Chapa 3.

Diferente do seu modelo de 2 polos, no de 3 polos o fio de uma bobina sempre se junta com o fio da próxima, formando um triângulo.

Para que os fios fiquem organizados e as bobinas fiquem retas, iremos visualizar o rotor de 6 cavidades como se fosse um relógio analógico. Os furos estarão posicionados exatamente nas marcações de: 12h, 2h, 4h, 6h, 8h e 10h.

O fio de cobre esmaltado será contínuo, não deveremos cortar o fio até finalizar a última bobina. Insira o fio pelo lado da frente do rotor (a face que fica de frente para o comutador) e retorne por trás.

### 🧵 Execução da Bobina A (Eixo 12h - 6h):
* **Início:** Pegue a ponta inicial do fio de cobre, raspe o verniz esmaltado para expor o metal e solde-a na Chapa 1.
* **Enrolamento:** Leve o fio até o furo das 12h (entrando da frente para trás do rotor), desça pelas costas da peça até o furo das 6h, e traga-o novamente para a frente (saindo nas 6h). Suba cruzando a frente do rotor até as 12h e repita esse ciclo (entra nas 12h -> sai nas 6h) até atingir o número de voltas desejado (por exemplo, 100 voltas).
* **Transição:** A última volta deve terminar obrigatoriamente com o fio saindo pelo furo das 6h na face da frente.
* **Fixação:** Puxe o fio das 6h direto para o centro (em direção ao comutador), raspe o esmalte apenas no ponto de contato e solde-o na Chapa 2. Não corte o fio.

### 🧵 Execução da Bobina B (Eixo 4h - 10h):
* **Início:** A partir da Chapa 2 onde você acabou de soldar, leve o fio até o furo das 4h na face da frente.
* **Enrolamento:** Passe o fio para trás do rotor (entrando nas 4h), leve pelas costas até o furo das 10h, e traga-o de volta para a frente (saindo nas 10h). Suba cruzando a frente do rotor até as 4h e repita o ciclo (entra nas 4h -> sai nas 10h) pelo mesmo número de voltas da bobina anterior. É normal os fios cruzarem no centro por cima da primeira bobina.
* **Transição:** A última volta deve terminar obrigatoriamente com o fio saindo pelo furo das 10h na face da frente.
* **Fixação:** Puxe o fio das 10h direto para o centro até o comutador, raspe o esmalte e solde-o na Chapa 3. Não corte o fio.

### 🧵 Execução da Bobina C (Eixo 8h - 2h):
* **Início:** A partir da Chapa 3, leve o fio até o furo das 8h na face da frente.
* **Enrolamento:** Passe o fio para trás do rotor (entrando nas 8h), leve pelas costas até o furo das 2h, e traga-o para a frente (saindo nas 2h). Suba cruzando a frente do rotor até as 8h e repita o ciclo (entra nas 8h -> sai nas 2h) mantendo a mesma quantidade de voltas das outras duas bobinas.
* **Transição:** A última volta deve terminar obrigatoriamente com o fio saindo pelo furo das 2h na face da frente.
* **Fechamento:** Puxe o fio final das 2h direto para o centro, raspe o esmalte e solde-o de volta na Chapa 1, juntando-o exatamente com o ponto onde tudo começou.
* **Fim:** Só agora, com o circuito fechado em formato de triângulo (Delta), você corta o fio do carretel.

## 🔬 Funcionamento e Dinâmica da Corrente
O funcionamento suave e contínuo do motor de 3 polos — configurado com enrolamento em Delta (triângulo) — baseia-se na distribuição ininterrupta da corrente elétrica. A geometria do comutador (composto por 3 segmentos a 120°) e o posicionamento estático das escovas (fixadas a 180°) garantem que o circuito elétrico nunca sofra interrupções.

A operação do motor pode ser dividida em dois estados mecânicos distintos, que se alternam continuamente durante a rotação do eixo:

### 🔄 Estado 1: Contato Singular (Giro Livre)
Este estado representa a maior parte do ciclo de rotação do motor, ocorrendo quando as escovas repousam sobre a região central das chapas de contato.
* **Posicionamento:** A escova de polaridade positiva faz contato exclusivo com a Chapa 1. A escova de polaridade negativa faz contato exclusivo com a Chapa 2. A Chapa 3 encontra-se isolada no espaço livre entre as duas escovas, sem contato elétrico direto com a fonte.
* **A Dinâmica da Corrente:** A tensão elétrica aplicada à Chapa 1 divide-se em dois ramos paralelos para atingir o polo negativo na Chapa 2:
  * **O Caminho Curto:** A corrente flui diretamente da Chapa 1 para a Chapa 2 através da Bobina A. Por apresentar a menor resistência elétrica, este ramo conduz a maior parcela da corrente, transformando a Bobina A em um eletroímã de alta intensidade. Este campo magnético principal é o responsável primário por gerar o torque mecânico.
  * **O Caminho Longo:** Simultaneamente, uma parcela da corrente flui da Chapa 1 para a Bobina C, atinge a Chapa 3 (que atua momentaneamente como um nó de passagem), atravessa a Bobina B e chega à Chapa 2. Nesta configuração, as Bobinas C e B operam em série e dividem a tensão. O campo magnético resultante é de menor intensidade, mas atua de forma suplementar para auxiliar a tração contínua do rotor.

### ⚡ Estado 2: Contato Duplo
Este estado ocorre na fração de segundo em que a fenda de isolamento (o vão entre os segmentos de cobre) transita exatamente sob uma das escovas.
* **Posicionamento:** Devido à sua largura física, a escova positiva encosta simultaneamente na Chapa 1 e na Chapa 3, estabelecendo uma "ponte" elétrica. A escova negativa, estando diametralmente oposta, permanece centralizada e isolada exclusivamente na Chapa 2.
* **A Dinâmica da Corrente:** Com a entrada simultânea de energia nas Chapas 1 e 3, a distribuição do circuito altera-se instantaneamente:
  * **A Bobina em Repouso:** Como a Chapa 1 e a Chapa 3 estão sob o mesmo potencial elétrico (ambas conectadas à escova positiva), a diferença de potencial ao longo da Bobina C torna-se nula. Consequentemente, a corrente não flui por esta bobina, neutralizando temporariamente seu campo magnético.
  * **Os Dois Caminhos Curtos (Paralelos):** O fluxo de energia ocorre, então, através de dois caminhos diretos e independentes em direção ao negativo. Uma parte flui da Chapa 1 através da Bobina A até a Chapa 2; a outra parte flui da Chapa 3 através da Bobina B até a Chapa 2.
Neste instante crítico, o circuito não é interrompido, o motor passa a operar com duas bobinas recebendo força máxima em paralelo. A geração desse campo magnético duplo garante que o rotor possua torque suficiente para transpor a zona de isolamento do comutador, eliminando a ocorrência de pontos de interrupção.

## 📚 Referências

* Documentação interna PETEE

## 👥 Equipe

* **Instituição:** PETEE – UFMG (Programa de Educação Tutorial em Engenharia Elétrica)

📢 **Licença:** Projeto aberto para fins didáticos e educacionais. Cite PETEE – UFMG ao utilizar este protótipo ou sua documentação.
