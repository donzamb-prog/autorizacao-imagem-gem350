# ⚜️ Autorização de Uso de Imagem, Voz e Dados - UEL

Aplicação web responsiva desenvolvida para o **Grupo Escoteiro Memorial 350 SP** destinada à recolha digital e gestão de termos de consentimento para uso de imagem, voz e dados de crianças e adolescentes (membros juvenis), conforme as diretrizes da União dos Escoteiros do Brasil (UEB) e a Lei Geral de Proteção de Dados (LGPD - Lei nº 13.709/2018).

---

## 🚀 Funcionalidades

* 📱 **Interface Responsiva e Intuitiva:** Adaptada para utilização simples em smartphones, tablets e computadores.
* ✍️ **Assinatura Digital no Ecrã:** Painel tátil para recolha de assinatura manual do responsável legal.
* 📄 **Conformidade com a LGPD e ECA:** Cláusulas detalhadas sobre finalidade, abrangência, gratuitidade e revogação.
* ☁️ **Integração Automática com Google Drive:** Ao assinar, a aplicação gera uma imagem do documento e guarda-a diretamente numa pasta dedicada no Google Drive do Grupo Escoteiro via Google Apps Script.
* ⚙️ **Execução Offline-First / GitHub Pages:** Hospedado gratuitamente através do GitHub Pages sem necessidade de servidores pagos.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
* **Assinatura Digital:** [Signature Pad](https://github.com/szimek/signature_pad)
* **Geração de Imagem/PDF:** [html2canvas](https://html2canvas.hertzen.com/) & [jsPDF](https://github.com/parallax/jsPDF)
* **Backend Serverless:** [Google Apps Script](https://developers.google.com/apps-script)
* **Armazenamento:** Google Drive API

---

## 📁 Estrutura do Repositório

```text
autorizacao-imagem-gem350/
├── index.html       # Aplicação principal (Formulário e Scripts)
├── logo_gem.png     # Logótipo do Grupo Escoteiro Memorial 350 SP
├── logo_ueb.png     # Logótipo da União dos Escoteiros do Brasil
├── LICENSE          # Licença de utilização (MIT)
└── README.md        # Documentação do projeto
