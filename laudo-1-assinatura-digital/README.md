# 🔒 Laudo Pericial nº 01  
## Análise de Integridade e Autenticidade de Assinatura Digital

---

## 🎯 Objetivo da Perícia
O presente trabalho pericial teve como objetivo determinar a **autenticidade** (identificação do signatário) e a **integridade** (verificação de alterações posteriores) do arquivo eletrônico `documento.pdf`, após questionamento formal da parte Autora quanto à validade da assinatura digital aposta no documento.

---

## 🔬 Metodologia e Evidências Técnicas
A perícia foi conduzida seguindo o rigor técnico da **Computação Forense**, em conformidade com a **Norma ABNT ISO/IEC 27037:2013**, garantindo a correta **cadeia de custódia da evidência digital**.

---

### 🧪 Preservação e Verificação de Integridade
- O código hash **SHA-256** da evidência foi calculado imediatamente após a coleta, utilizando a ferramenta **HashCalc**.
- **HASH SHA-256 da evidência:**
0d6adc9d0863c9dfe8ca16accbb31312ef8d657205edb739a156c38df62cb973
- A captura de tela do cálculo do hash encontra-se documentada na pasta `imagens/`.

---

### 🧾 Análise de Metadados
- A ferramenta **ExifTool** foi utilizada para a extração de metadados ocultos do arquivo.
- Foram identificadas informações como:
- Software de criação: Microsoft Word para Microsoft 365
- Autor do documento: **Joao Benedito dos Santos Junior**
- Datas de criação e modificação
- As evidências da extração de metadados estão registradas em imagens anexas.

---

### ⏱️ Análise Temporal – Carimbo do Tempo (Timestamp)
- A data e hora exatas da assinatura digital foram extraídas por meio da ferramenta **XolidoSign**.
- **Data da assinatura:** 04/11/2024 às 19:34:35 (UTC−03:00)

---

### 🏛️ Validação Oficial da Assinatura Digital
- O documento assinado foi submetido ao validador oficial do Governo Federal (**validar.iti.gov.br**), para verificação de validade jurídica perante a **ICP-Brasil**.
- O sistema oficial **reprovou a assinatura digital**, apontando inconsistências relacionadas à integridade do arquivo.

---

## ⚖️ Conclusão Pericial
Em conformidade com o **Artigo 473 do Código de Processo Civil**, conclui-se tecnicamente que:

- **Identificação do Signatário:**  
A assinatura digital foi aposta pelo titular **JOAO BENEDITO DOS SANTOS JUNIOR**, em 04/11/2024.

- **Quebra de Integridade:**  
O documento analisado foi **modificado após a aposição da assinatura digital**, conforme constatado na validação oficial do ITI.

- **Resposta ao Quesito 5:**  
**SIM**, há evidências técnicas de edição do arquivo após a inserção da assinatura digital.

- **Resultado Final (Quesito 6):**  
Devido à violação da integridade do documento, a assinatura digital é considerada **inválida perante a ICP-Brasil**, não possuindo validade jurídica.

---

## 📎 Documentação e Evidências
- 📄 **Laudo Pericial Final:** `LAUDO_DOC_ASS_DIG.pdf`
- 📄 **Quesitos Periciais:** `quesitosPericiaisInvestigacaoPericiaInteligenciaDocumentosAssinaturasDigitais.pdf`
- 📄 **Documento Analisado:** `documento.pdf`
- 📂 **Evidências Visuais:** pasta `imagens/`

---

## 🧑‍💻 Executor da Perícia
**João Gustavo Pires da Costa**  
Curso: Ciência da Computação  
Disciplina: **Segurança e Criptografia de Dados**  
Instituição: Pontifícia Universidade Católica de Minas Gerais – PUC Minas
