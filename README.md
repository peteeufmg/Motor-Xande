# ⚙️ Motor Xande – Protótipo Didático

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
| **Corrente** | Variável | A corrente será definida pela demanda de torque e resistência das bobinas. |

## 🛠️ Guia de Manutenção Simples

Para garantir o bom funcionamento e a durabilidade do protótipo, realize as seguintes verificações periodicamente:

1. **Ajuste da Tensão das Escovas:** Com o uso, as lâminas metálicas laterais (escovas) podem perder a elasticidade e afastar do eixo. Dobre-as levemente para dentro com os dedos para garantir que mantenham um contato elétrico firme com o comutador, mas sem apertar demais para não frear o motor por excesso de atrito mecânico.
2. **Limpeza do Comutador:** O atrito contínuo entre as escovas e o comutador pode gerar resíduos escuros ou oxidação, prejudicando a condução elétrica. Limpe os quatro segmentos do comutador periodicamente.
3. **Inspeção das Conexões:** Verifique visualmente se os fios vermelho e preto continuam bem soldados nas bases das escovas metálicas e se os bornes de conexão não estão frouxos ou com fios rompidos.
4. **Verificação do Eixo e Atrito:** Com o motor desligado, gire o eixo central com a mão. Ele deve girar livremente, sem "agarrar".
   
## 📚 Referências

* Documentação interna PETEE

## 👥 Equipe

* **Instituição:** PETEE – UFMG (Programa de Educação Tutorial em Engenharia Elétrica)

📢 **Licença:** Projeto aberto para fins didáticos e educacionais. Cite PETEE – UFMG ao utilizar este protótipo ou sua documentação.
