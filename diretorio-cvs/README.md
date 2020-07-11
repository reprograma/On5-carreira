# reprograma-CV
Código criado para a página de currículos da {reprograma}

## Orientações github
- Clonar este repositório: `https://github.com/reprograma/On5-carreira`
- Crie sua branch: `git checkout -b seuNome`, ex: `git checkout -b fulanaBarbosa`
- Trabalhe dentro da sua branch fazendo todos os commits e pushs direcionados para ela, ao finalizar o projeto realizar o `pull request` para a master

## Para adicionar seu currículo:
- Crie uma pasta com seu *nome-sobrenome* (como a pasta exemplo **fulana-barbosa**) dentro da pasta **students**.
- Copie e cole o **cv_fulana-barbosa.html** (que está dentro da pasta exemplo **fulana-barbosa**) e remeie com seu *cv-nome-sobrenome*.

![alt text](./assets/img/pastas.png)

### No index.html:
- Na section `class="students"`, copie a div abaixo e substitua com seu nome **id="nome-sobrenome"**.
- Complete o link para a págino do seu currículo em **href="./students/fulana-barbosa/cv-fulana-barbosa.html"**. Não esqueça de substituir `fulana-barbosa` pelo seu nome-sobrenome

```html
<div id="fulana-barbosa" class="student">
    <div class="name">
        { Fulana Barbosa }
    </div>
    <a class="button" href="./students/fulana-barbosa/cv-fulana-barbosa.html">ver mais</a>
</div>
```
