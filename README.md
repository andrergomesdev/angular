# Angular
Projeto utilizado para o aprendizado do angular framework.

## Introdução
Angular é um framework javascript que permite criar *SPA* (Single Page Applications) reativas. Transições de telas não precisam ir no servidor e carregar informações de forma **síncrona**. As páginas já são pré-carregadas dando ao usuário a sensação de fluidez e quando necessário os dados são carregados **assíncronamente**.  

## Evolução
Angular 1 - Também conhecido como **AngularJS** foi a priveira versão do framework. Esta versão, apesar de ter sido muito difundida, apresentou alguns problemas que fizeram com o que o time responsável pelo framework fizesse uma restruturação do framework praticamente criando um novo.  
Angular 2 (2016) - Lançamento de uma nova versão mas com profundas mudanças em relação ao AngularJS.  
~~Angular 3~~ (Não houve a versão 3)  
Angular 4 (posteriormente as versões foram lançadas a cada 6 meses)  
...  
Angular 10 (Atual)  

## Comandos

- Atualizar **npm**:  
```cmd
npm install -g npm
```

- Atualizar **Cli**:
```cmd
npm uninstall -g angular-cli @angular/cli  
npm cache verify  
npm install -g @angular/cli  
```

- Criar um projeto angular via Cli
```cmd
ng new project_name  -- Não utilizar o nome test, pois test é uma palavra reservada
```

- Executar o projeto Angular (node como servidor)
```cmd
ng serve  -- O Servidor por padrão executa na porta 4200.
```

## Problemas comuns
- Ao tentar criar um projeto no windows acontece as vezes de demorar mais que 3 minutos.  
**Dica**: executar o CMD como administrador  
- Ao tentar subir o serviço tomar um error *Address already in use*.  
Provavelmente você tem outro serviço rodando na porta 4200 padrão do angular. Tentar executar o serviço em outra porta utilizando o comando *ng serve --port ANOTHERPORT*  
- As mudanças realizadas não estão refletindo na execução.  
Verificar se o *ng serve* exibe algum erro de execução. Se não for o caso, verificar se está utilizando a última versão do **Cli** e reiniciar.

## Estrutura de arquivos e pacotes
package.json -> Lista as dependências do projeto.  
node_modules -> pasta onde as dependências estão instaladas.    

## Tópicos abordados no projeto
1. O básico  
2. Componentes e Databinding  
3. Diretivas  
4. Observables  
5. Rotas  
6. Serviços e Injeção de dependência  
7. Forms  
8. Pipes  
9. Http  
10. Autenticação  
11. Otimizações e NgModules  
12. Deployment  
13. Animações e Testing  



