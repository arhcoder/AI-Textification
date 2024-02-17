# 📚 PROYECTO AI-TEXTIFICATION
## 👅 Procesamiento de Lenguaje Natural
## 💻 Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas
## 💻 Facultad de Ciencias
## 🏫 Universidad Nacional Autónoma de México

<hr>

### 🤖 AI-TEXTIFICATION
### 📄 Detección de autoría en textos AI - Humanos:

#### 🔵 **Tarea A**: Clasificación Binaria:
1. Texto de Humano.
2. Texto de Inteligencia Artificial.

#### 🔵 **Tarea B**: Clasificación Multiclase:
1. Texto de ChatGPT.
2. Texto de Cohere.
3. Texto de Davinci.
4. Texto de Dolly.
5. Texto de Humano.

**👬 Autores:**
* Alejandro Ramos @arhcoder.
* Manuel León Rosas..

# 🎯 Objetivo

**EN ESTE NOTEBOOK SE OBTENDRÁ EL DATASET Y SE LE APLICARÁN TRANSFORMACIONES DE PREPROCESAMIENTO CON DISTINTAS COMBINACIONES:**

1. **PA: Cleaned => Lemma => UNK => ~GENSIM Embbedings~**.
2. **PB: Cleaned => Lemma => UNK => ~OWN Embbedings~**.
3. **PC: Cleaned => UNK => ~GENSIM Embbedings~**.
4. **PD: Cleaned => UNK => ~OWN Embbeds~**.

**ALSO USING NEURAL NETWORKS TECHNIQUES**.

# 📓 Dataset

## SemEval2024-task8
### Fuente: https://github.com/mbzuai-nlp/SemEval2024-task8
### Información del dataset:

#### **SemEval-2024 Task 8: Multigenerator, Multidomain, and Multilingual Black-Box Machine-Generated Text Detection**

> Large language models (LLMs) are becoming mainstream and easily accessible, ushering in an explosion of machine-generated content over various channels, such as news, social media, question-answering forums, educational, and even academic contexts. Recent LLMs, such as ChatGPT and GPT-4, generate remarkably fluent responses to a wide variety of user queries. The articulate nature of such generated texts makes LLMs attractive for replacing human labor in many scenarios. However, this has also resulted in concerns regarding their potential misuse, such as spreading misinformation and causing disruptions in the education system. Since humans perform only slightly better than chance when classifying machine-generated vs. human-written text, there is a need to develop automatic systems to identify machine-generated text with the goal of mitigating its potential misuse.

> We offer three subtasks over two paradigms of text generation: (1) full text when a considered text is entirely written by a human or generated by a machine; and (2) mixed text when a machine-generated text is refined by a human or a human-written text paraphrased by a machine.


**Subtasks**

> **Subtask A.** Binary Human-Written vs. Machine-Generated Text Classification: Given a full text, determine whether it is human-written or machine-generated. There are two tracks for subtask A: monolingual (only English sources) and multilingual.

> **Subtask B.** Multi-Way Machine-Generated Text Classification: Given a full text, determine who generated it. It can be human-written or generated by a specific language model.

> **Subtask C.** Human-Machine Mixed Text Detection: Given a mixed text, where the first part is human-written and the second part is machine-generated, determine the boundary, where the change occurs.

**Downloading**

| Task | File ID |
|------|---------|
| Whole dataset | 14DulzxuH5TDhXtviRVXsH5e2JTY2POLi
| Subtask A |	1CAbb3DjrOPBNm0ozVBfhvrEh9P9rAppc |
| Subtask B |	11YeloR2eTXcTzdwI04Z-M2QVvIeQAU6- |
| Subtask C |	16bRUuoeb_LxnCkcKM-ed6X6K5t_1C6mL |