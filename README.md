
# 🧠 Projeto de Reconhecimento de Texto com OCR e Inteligência Artificial

Este projeto foi desenvolvido como parte do bootcamp **DecolaTech Avanade 2025**, com o objetivo de aplicar tecnologias modernas de **OCR (Reconhecimento Óptico de Caracteres)** combinadas com **Inteligência Artificial da Microsoft Azure**, **Java com Spring Boot** no backend e **Angular** no frontend.

---

## 🎯 Objetivo

Realizar a extração automática de texto a partir de imagens (OCR), processar esses dados com Java + Spring Boot, exibir na interface web construída em Angular e explorar os serviços de IA da Microsoft Azure para gerar análises inteligentes.

---

## 📂 Estrutura do Projeto

```
📦 projeto-ocr-azure
├── inputs/               # Imagens utilizadas no processo
├── output/               # Textos extraídos das imagens
├── backend/              # Java + Spring Boot
│   └── src/
├── frontend/             # Angular
│   └── src/
└── README.md             # Este arquivo
```

---

## 🚀 Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3**
- **Angular 16+**
- **Microsoft Azure Cognitive Services (IA)**
- **Azure Computer Vision API**
- **Git & GitHub**

---

## 📥 Inputs

As imagens utilizadas foram obtidas do repositório público:

🔗 [`PauloPRBM/Imagens`](https://github.com/PauloPRBM/Imagens)

Incluem:
- Documentos digitalizados
- Capturas de tela
- Imagens com texto manuscrito

---


---

## 🖼️ Exemplo de Extração

### Imagem:
`inputs/exemplo1.jpg`

### Texto extraído:
```
"Certificamos que o aluno concluiu com êxito o curso de Programação Web com carga horária de 80 horas."
```

---

## 🧠 Azure IA: Geração de Insights

Os textos extraídos foram enviados para o serviço **Azure OpenAI** para realizar:

- **Resumos automáticos**
- **Classificação por categorias**
- **Sugestões inteligentes** com base no conteúdo
- **Geração de respostas automatizadas**

---

## 💻 Como Executar o Projeto

### Pré-requisitos

- Java 17+
- Node.js + Angular CLI
- Conta Azure com Cognitive Services
- IDE (VS Code, IntelliJ, etc)

### 1. Backend (Spring Boot)

```bash
cd backend
./mvnw spring-boot:run
```

### 2. Frontend (Angular)

```bash
cd frontend
npm install
ng serve
```

---

## 💡 Insights e Aprendizados

- OCR com IA pode transformar imagens em dados úteis e inteligentes.
- Textos com boa qualidade de imagem geram resultados precisos.
- A IA da Azure permite análises rápidas, personalizadas e automatizadas.
- A integração entre backend, frontend e IA é essencial para criar soluções completas.

---

## 🌐 Possibilidades Futuras

- Tradução automática dos textos extraídos
- Geração de relatórios em PDF com IA
- Armazenamento em banco de dados para buscas inteligentes
- Análise de sentimentos e classificação de conteúdo
- Dashboard com Power BI para visualização dos dados extraídos

---

## 📎 Links úteis

- [Microsoft Azure Cognitive Services](https://azure.microsoft.com/en-us/products/cognitive-services/)
- [Azure Computer Vision API](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/)
- [OpenAI no Azure](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
- [Angular CLI Docs](https://angular.io/cli)
- [Spring Boot Docs](https://spring.io/projects/spring-boot)

---

## 🤝 Contribuição

Sugestões, melhorias ou correções são bem-vindas! Sinta-se à vontade para abrir uma issue ou pull request.

---

### 💼 Projeto desenvolvido para fins educacionais | Bootcamp **DecolaTech Avanade 2025** 🚀
