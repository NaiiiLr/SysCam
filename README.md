# SysCam 

O **SysCam** é uma plataforma de monitoramento de câmeras de segurança com backup em nuvem, desenvolvida com uma arquitetura de **Monorepo** para manter o Frontend e o Backend perfeitamente separados, porém sob o mesmo controle de versão.

---

##  Estrutura do Projeto

O projeto é dividido em pastas independentes:

* **/frontend**: Interface web moderna desenvolvida em Next.js.
* **/backend**: (Em planejamento) API de processamento e persistência.

**Gitignore Global**
O projeto utiliza um .gitignore na raiz que protege ambas as pastas

---

## Frontend (Next.js)

A interface foi construída focando em performance extrema e experiência do usuário (UX).

### Tecnologias Principais
* **Next.js 15+** (App Router)
* **TypeScript** (Tipagem estática)
* **Styled Components** (Estilização via CSS-in-JS com SSR)
* **React Compiler** (Otimização automática de performance)

## Como Rodar o Frontend

1. **Acesse a pasta do front:**
   cd frontend

2. **Instale as dependências:** 
  npm install

3. **Inicie o servidor de desenvolvimento:**
  npm run dev

---

### Fluxo de Desenvolvimento (Git) ###
A branch main deste repositório é protegida. Para contribuir e manter a organização do monorepo, siga os passos:

1. **Crie uma nova branch para sua tarefa:**
  git checkout -b feat/nome-da-feature

2. **Realize o commit das alterações:**
git add .
git commit -m "feat: descrição da melhoria ou correção"

3. **Suba a branch para o GitHub:**
git push origin feat/nome-da-feature

4. **Abra um Pull Request:**
Acesse a interface do GitHub para realizar a revisão e o merge para a branch main.
