# 📋 Ficha de Cadastro – Novo Colaborador

Formulário web para admissão de colaboradores, desenvolvido para uso em escritórios de contabilidade e departamento pessoal.

## ✨ Funcionalidades

- Preenchimento automático de endereço via CEP (API ViaCEP)
- Geração de PDF diretamente no navegador (html2pdf.js)
- Envio de mensagem pré-formatada via WhatsApp
- Campos condicionais: dependentes, trabalho aos sábados, vale-transporte e deficiência aparecem apenas quando necessário — inclusive no PDF
- **Sem armazenamento de dados no navegador** — em conformidade com a LGPD
- Separação visual entre dados da empresa e dados do colaborador

## 📁 Versões

| Arquivo | Descrição |
|---|---|
| `FICHA_CADASTRO_Escritorio.html` | Versão para uso interno no escritório |
| `FICHA_CADASTRO_Portfolio.html` | Versão portfólio com identidade visual diferenciada |

## 🚀 Como usar

Basta abrir o arquivo `.html` no navegador. Não requer instalação, servidor ou internet (exceto para preenchimento automático por CEP e carregamento de fontes).

## 🛠️ Tecnologias

- HTML5, CSS3, JavaScript (vanilla)
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — geração de PDF no navegador
- [ViaCEP](https://viacep.com.br/) — consulta de CEP

## ⚖️ Conformidade

- Sem uso de `localStorage` ou `sessionStorage`
- Nenhum dado é transmitido a servidores externos (exceto a consulta ao ViaCEP pelo CEP informado)
- Registro em carteira digital conforme **Portaria MTE nº 1.065/2023**

## 👤 Autor

Desenvolvido por **João Miguel E. F.**  
contato_joaomiguel@outlook.com  

> Uso, cópia ou adaptação somente com autorização do autor.
> 
