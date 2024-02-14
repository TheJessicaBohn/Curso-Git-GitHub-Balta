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
    - No seu repositório tem a opção de ir em **Actions** e depois escolher qual o tipo de plataforma você deseja criar e clicar em **Configure**, como mostra a imagem
     ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/49e121f5-fd76-4f5f-b2ce-57ee1234387b)
    - Aqui ele dá um exemplo de Action para você colocar no seu repositório:
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/7a23db8e-18ee-44c8-b93f-c778af5008ae)
    - Apos criado o seu file de Actions é preciso criar uma chave SSH e subistituir o trecho seguinte:
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/f0e9fa52-04c0-400f-b18e-3aa4de1a935f)
    - É necesserio criar uma pasta, abrir no terminal e executar o seguinte comando ```ssh-keygen -t rsa -b 4096 -C "(git config user.email)" -f "<your-deploy-branch>" -N ""```
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/84964ac3-301f-423c-b137-a0e10e1ba754)
    - Para fazer nosso Deploy é necessário antes criar uma branch pra isso, como na imagem abaixo:
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/9c1b9ce9-4504-4a4e-9272-42f0391122ea)
    - Em nosso repositório vá em **Settings** e depois em **Pages**:
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/1bb2197b-2cc9-4a72-a73c-b6ce186928f9)
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/06d41441-3afe-4f48-b4ae-f852de459c62)
    - Escolha **Deploy from a branch** e escolha a branch que você criou no passo anterior:
      ![image](https://github.com/TheJessicaBohn/Curso-Git-GitHub-Balta/assets/47541659/8ef41326-b803-4f74-895b-bdf87ce6b853)

  




