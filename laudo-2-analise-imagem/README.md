# 📷 Laudo Pericial nº 02  
## Análise Forense em Imagem Digital  
**Arquivo analisado:** `placaMoto.jpeg`

---

## 🎯 Objetivo da Perícia
O presente trabalho pericial teve como objetivo a **análise forense da imagem digital** `placaMoto.jpeg`, visando responder aos quesitos formulados pela parte Autora, com foco em:

- Verificação da **integridade do arquivo**
- Análise temporal da captura da imagem
- Detecção de possíveis **adulterações**
- Extração de informações visuais relevantes
- **Estimativa da altura do condutor** da motocicleta

---

## 🔬 Metodologia e Evidências Técnicas
A perícia foi conduzida conforme as diretrizes do **DFIR (Digital Forensics and Incident Response)** e em conformidade com a **Norma ABNT ISO/IEC 27037:2013**, garantindo a correta preservação da **cadeia de custódia da evidência digital**.

---

## 🧪 Preservação e Verificação de Integridade
- **Objeto da perícia:** Arquivo de imagem digital no formato JPEG, denominado `placaMoto.jpeg`.
- As funções hash foram calculadas utilizando a ferramenta **HashCalc**, assegurando a integridade da evidência.

**HASHs de Integridade:**  

MD5: d4233db838cf71eab9e1127a22e21803  

SHA-256: 422f9d56432f14f0d07e26b6df625447b41e6a9b77311cb8324e8e3c5913f8f9

- As capturas de tela do cálculo das HASHs encontram-se documentadas na pasta `imagens/`.

---

## 🧾 Análise de Metadados e Temporal
- A extração de metadados foi realizada com a ferramenta **ExifTool**.
- O campo **DateTimeOriginal** não estava presente no arquivo.
- A data mais confiável identificada foi o **timestamp embutido na imagem**, indicando:
  - **Data e hora da captura:** 12/01/2017 às 10:40:39

- As evidências da análise de metadados encontram-se registradas nas imagens anexas.

---

## 🔍 Análise de Adulteração – ELA
- Foi realizada análise de integridade por meio da técnica **ELA (Error Level Analysis)** utilizando a ferramenta **Forensically**.
- **Conclusão técnica:**  
  Não foram identificados sinais de adulteração na imagem. O padrão de compressão apresentou-se uniforme, indicando que o arquivo é um **snapshot de sistema de vigilância (DVR)**, sem manipulação posterior.

---

## ⚖️ Conclusão Pericial – Resultados e Respostas aos Quesitos

### 📌 Análise de Conteúdo
- **Quesito 9 – Identificação da Placa:**  
  **NÃO** foi possível identificar a placa da motocicleta de forma conclusiva. A baixa resolução e o nível de ruído da imagem impediram a leitura inequívoca dos caracteres, mesmo após processamento digital.

- **Quesito 11 – Estimativa de Altura:**  
  **SIM**, foi possível estimar a altura do condutor.

### 📐 Processamento e Medição
- A estimativa foi realizada com o software **ImageJ/Fiji**, utilizando técnica de **calibração de escala** baseada em elementos de referência presentes na imagem.
- **Altura estimada do condutor:** **1,87 metros**  
  (Valor exato: **1,865 m**)

- As capturas de tela da medição encontram-se documentadas na pasta `imagens/`.

---

## 🏁 Conclusão Final
A análise forense confirmou que a imagem examinada possui **integridade preservada**, não apresenta sinais de adulteração e corresponde a um **snapshot de sistema de vigilância**.  

Foi possível estimar tecnicamente a altura do condutor em **1,87 metros**, porém **não foi possível identificar a placa da motocicleta** devido às limitações técnicas impostas pela qualidade da imagem.

---

## 📎 Documentação e Evidências
- 📄 **Laudo Pericial Final:** `LAUDO_IMAGENS.pdf`
- 📄 **Imagem Analisada:** `placaMoto.jpeg`
- 📂 **Evidências Visuais:** pasta `imagens/`

---

## 🧑‍💻 Executor da Perícia
**João Gustavo Pires da Costa**  
Curso: Ciência da Computação  
Disciplina: **Segurança e Criptografia de Dados**  
Instituição: Pontifícia Universidade Católica de Minas Gerais – PUC Minas
