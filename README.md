# Templates LaTeX para Artigos Científicos 📄✒️

Bem-vindo ao repositório de **Templates LaTeX para Artigos Científicos**! 

Este é um espaço centralizado que reúne modelos prontos para a redação e submissão de artigos. Ele foi criado com o objetivo de padronizar documentos acadêmicos, facilitar o atendimento às exigências de periódicos internacionais e tornar a escrita científica muito mais fluida.

## 🎯 Nosso Objetivo

Este repositório foi desenvolvido pensando em:
* **Facilitar a escrita científica** tirando o peso da formatação manual através do LaTeX.
* **Disponibilizar templates prontos** para submissão direta em revistas científicas de alto impacto.
* **Padronizar a estrutura** de artigos e manuscritos dentro de grupos de pesquisa.
* **Reduzir erros de formatação** que costumam atrasar o processo de revisão e submissão.
* **Aumentar a produtividade** para que o foco fique 100% no conteúdo da pesquisa.

---

## 📚 Templates Disponíveis

Atualmente, o repositório conta com os seguintes modelos prontos para uso:

1. [**ACS (American Chemical Society):**](./ACS)
Template oficial adaptado para uso prático. Ele inclui:
* Estrutura completa de artigo (Resumo, Introdução, Metodologia, Resultados, Conclusões).
* Gerenciamento dinâmico de referências via BibTeX.
* Formatação nativa e estritamente compatível com os periódicos da ACS.

*(Novos templates para Elsevier, Springer, MDPI, entre outros, serão adicionados futuramente!)*

---

## 🚀 Como baixar e utilizar os templates

Você pode utilizar estes templates tanto na nuvem (via Overleaf) quanto no seu próprio computador. Siga o passo a passo abaixo:

### Passo 1: Obtenha os arquivos do repositório
Você tem duas opções para fazer isso:

**Opção A (Ideal para usar no Overleaf):** 1. No topo desta página, clique no botão verde escrito **"<> Code"**.
2. Clique em **"Download ZIP"**.
3. Extraia a pasta `.zip` no seu computador.

**Opção B (Para quem usa Git e editores locais):**
Abra o seu terminal e digite:
```bash
git clone [https://github.com/SEU_USUARIO/Templates-LaTeX-para-Artigos-Cientificos.git](https://github.com/SEU_USUARIO/Templates-LaTeX-para-Artigos-Cientificos.git)
cd Templates-LaTeX-para-Artigos-Cientificos
```
*(Lembre-se de substituir `SEU_USUARIO` pelo seu usuário real do GitHub)*

### Passo 2: Abra o template no seu editor favorito

**Se for usar o Overleaf (Nuvem):**
1. Acesse o [Overleaf](https://www.overleaf.com/) e faça login.
2. Clique em **"New Project"** e depois em **"Upload Project"**.
3. Selecione o arquivo `.zip` específico do template que você quer usar (ex: a pasta compactada do template ACS).
4. O Overleaf vai compilar tudo automaticamente e você já pode começar a escrever!

**Se for usar localmente (VS Code, TeXstudio, etc):**
1. Certifique-se de ter uma distribuição TeX instalada no seu computador (como TeX Live ou MiKTeX).
2. Abra a pasta do template desejado no seu editor.
3. Edite o arquivo principal `.tex` e compile usando `pdflatex` ou a extensão do seu editor.

---

## ➕ Como adicionar novos templates

Este repositório é colaborativo e expansível. Para adicionar um novo template (como o da Elsevier ou Springer), siga este padrão para manter a organização:

1. Crie uma nova pasta na raiz do repositório com o nome da editora/revista (Ex: `/Elsevier`).
2. Adicione todos os arquivos necessários (`.tex`, `.cls`, `.sty`, e a pasta de imagens) dentro dela.
3. Inclua um arquivo `exemplo.bib` com algumas referências de teste.
4. Atualize a seção **"Templates Disponíveis"** neste `README.md` incluindo o novo número na lista e uma breve descrição do que o template contém.
