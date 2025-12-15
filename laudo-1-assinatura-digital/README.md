# 🔒 Laudo Pericial 1: Análise de Integridade e Autenticidade de Assinatura Digital

## 🎯 Objetivo da Perícia
[cite_start]O trabalho pericial teve como objetivo determinar a **autenticidade** (quem assinou?) e **integridade** (houve alterações?) do arquivo `documento.pdf` [cite: 14][cite_start], com foco na validação da assinatura digital após questionamento da parte Autora[cite: 13, 14].

---

## 🔬 Metodologia e Evidências Técnicas

[cite_start]O trabalho seguiu o rigor científico da Computação Forense [cite: 10] [cite_start]e a Norma **ABNT ISO/IEC 27037:2013** [cite: 11][cite_start], garantindo a cadeia de custódia da evidência digital[cite: 11].

### Preservação e Verificação de Integridade
* [cite_start]O código HASH SHA-256 de Cadeia de Custódia foi calculado imediatamente com a ferramenta **HashCalc**[cite: 37].
* [cite_start]**HASH SHA-256 da Evidência:** `0d6adc9d0863c9dfe8ca16accbb31312ef8d657205edb739a156c38df62cb973`[cite: 25, 38]. 

### Análise de Metadados e Temporal
* [cite_start]A ferramenta **ExifTool** foi utilizada para extrair metadados ocultos, como software de criação, autor e *timestamps* de modificação e criação[cite: 40]. 
* [cite_start]**Metadados:** Foi identificado que o documento foi criado com o **Microsoft Word para Microsoft 365** [cite: 52] [cite_start]pelo autor "Joao Benedito dos Santos Junior"[cite: 52].
* [cite_start]**Carimbo do Tempo (Timestamp):** A data exata da aposição da assinatura foi extraída pela ferramenta **XolidoSign** [cite: 41, 54][cite_start]: `04/11/2024 19:34:35-0300`[cite: 55]. 

### Validação Oficial
* [cite_start]O arquivo com a assinatura digital foi submetido ao validador oficial do Governo Federal, o **validar.iti.gov.br**, para verificar sua validade jurídica perante a ICP-Brasil[cite: 43]. 

---

## ⚖️ Conclusão Pericial: Quebra de Integridade e Adulteração

[cite_start]Em cumprimento ao Artigo 473 do CPC[cite: 9, 63], o Perito concluiu tecnicamente que:

* [cite_start]**Identificação do Signatário:** A assinatura foi aposta pelo titular **JOAO BENEDITO DOS SANTOS JUNIOR** [cite: 64] [cite_start]em **04/11/2024**[cite: 64].
* [cite_start]**Quebra de Integridade:** O documento foi submetido à validação oficial no portal do ITI, o qual **REPROVOU** a assinatura digital[cite: 65].
* [cite_start]**Motivo da Adulteração:** A razão formal da reprovação é a comprovação de que o **"Documento foi modificado após a assinatura"**[cite: 57, 66].
* [cite_start]**Resposta ao Quesito 5:** **SIM**, há sinais de edição do arquivo após a inserção da assinatura digital[cite: 56, 57].
* [cite_start]**Resultado Final (Quesito 6):** Devido à violação da integridade, a assinatura é considerada **inválida** perante a ICP-Brasil[cite: 59, 67].
