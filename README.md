<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0083cc&height=150&section=header"/>

# Projeto Criando sua primeira Landing Page com HTML e CSS
Neste incrível projeto disponibilizado pela Dio para os participantes do Bootcamp Ri Happy - Front-end do Zero, a principal ideia era aprendermos mais sobre HTML e CSS na prática e fixarmos ainda mais diversos conceitos vistos durante o curso. Também era opcional que cada aluno acrescentasse em seu projeto o seu "próprio toque". Sendo assim, fiz algumas melhorias que vi necessidade durante o desenvolvimento.

### 🔵 Mudanças no CSS
Na parte visual, decidi criar um efeito de cores no background da página, além de alguns pequenos detalhes, como adicionar um link ao botão e realizar alterações nas cores e tamanhos das letras de forma geral. Segue abaixo as alterações:
```
CSS

body {
  
  background: linear-gradient(to bottom, #000000, #092835, #6e741f); /* 🔵 Define um gradiente de fundo do topo para o fundo */
  background-size: 100% 200%; /* 🔵 Ajusta o tamanho do fundo para cobrir a área com um gradiente maior */
  animation: gradientAnimation 8s ease infinite; /* 🔵 Aplica a animação do fundo com duração de 8 segundos */
  user-select: none; /* 🔵 Desativa a seleção de texto pelo usuário */
  
}
@keyframes gradientAnimation {
    0% {
        background-position: 0% 0%; /* 🔵 Define a posição inicial do fundo */
    }
    50% {
        background-position: 0% 50%; /* 🔵 Muda a posição do fundo para meio da altura */
    }
    100% {
        background-position: 0% 0%; /* 🔵 Retorna a posição inicial do fundo */
    }
}

.banner .banner-content button {
  color: #31A8DD;
  font-size: 1rem;
  font-weight: bold;
  padding: 16px 32px;
  text-transform: uppercase;
  letter-spacing: 4px;
  background-color: transparent;
  border-image: linear-gradient(#3BA1CD, #1572B7);
  border-image-slice: 10;
  border-radius: 30px;
  cursor: pointer; /* 🔵 Aparecer o cursos quando estiver em cima do botão */
}       
```

```
HTML
 <a href="https://dio.me"> <button>Quero me inscrever</button></a>       
```

### 📋O que foi necessário para realizar este projeto

O projeto consistiu em configurar e executar um ambiente de desenvolvimento utilizando ferramentas essenciais. Primeiramente, foi necessário instalar o Git para o controle de versões.

Uma IDE (Ambiente de Desenvolvimento Integrado) foi configurada para facilitar a codificação, e, neste caso, optei pelo Visual Studio Code (VSCode). O projeto foi executado via a extensão do VSCode chamada Live Server. Após o desenvolvimento, o código foi versionado e compartilhado em um repositório no GitHub, garantindo o backup e o gerenciamento das versões do projeto.

Abaixo, deixarei alguns links para downloads oficiais de tudo o que foi utilizado para Windows.

```
 Visual Studio Code - https://code.visualstudio.com/
```
```
 GitBash - https://git-scm.com/downloads/win
```
```
 ID da extensão Live Server - ritwickdey.LiveServer
```
### 🪄Link do Projeto
Clique [aqui](https://jheniffermoraes.github.io/trilha-css-desafio-01/) e acesse o projeto!

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0083cc&height=100&section=footer"/>
