# Curso-Git-GitHub-Balta

- **Ferramentas Utilizadas:** [Git CLI](https://cli.github.com), [Git SCM](https://git-scm.com/download/win);

- GitHub:
  - OverView:
 
- **Fazendo Deploy Automatico**:
    - Verificar se existe algum remote adicionado ```git remote -v```;
    - Adicionando um repositorio de origem ```git remote add origin https://github.com/TheJessicaBohn/carnacode-balta-2024-desafio-03```
    - Enviando o código para o repositório ```git push -u origin main```;
 
- **GitHub Actions**
    - Série de scripts apara automatizar repositório, exemplo, rodar a build, ou então rodar os testes;
    - Ele também é chamado de workflow;
    - Para criar uma action no seu projeto, é necessário criar duas pastas chamadas uma dentro da outra ```.github/workflows```;
    - Dentro da pasta ```workflows``` criar um novo arquivo, claroque dependo do script qur você queira criar exemplo ```build.yml```;
