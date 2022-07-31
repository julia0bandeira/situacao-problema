# situacao-problema
resolvendo situação problema da empresa

passo-a-passo: principais comandos

comandos usados: 
git init
git status
git add
git commit -m
git remote add origin
git push -u origin master
git pull
git checkout
git push origin

-> segue o passo a passo dos meus comandos da primeira atividade de versionamento :)

1- criei uma pasta chamada "situação-problema", depois uma subpasta chamada "resolvendo-problema"
2- abri o GIT BASH
3- usei o "git init" pra iniciar um repositório Git vazio
4- criei um repositório online no GitHub com o mesmo nome da minha subpasta
5- criei um .txt chamado "alteracoes.txt" na subpasta
6- usei o "git status" pra verificar se o .txt consta na branch master (consta mas não foi adicionado e nem commitado)
7- usei o "git add ." pra adicionar qualquer coisa não adicionada na branch
8- usei o "git status" novamente pra verificar e o .txt foi adicionado mas não commitado ainda
9- usei o "git commit -m "solução para preservar o histórico de alterações do código-fonte do projeto"" para commitar o .txt no repositório
10- usei "git remote add origin https://github.com/julia0bandeira/situacao-problema.git" pra linkar o meu repositório do Git com o repositório online
11- usei o "git push -u origin master" pra confirmar esse link entre os repositórios
obs: tentei fazer isso antes de criar o primeiro .txt, mas não deu certo. aparentemente precisa commitar pelo menos uma coisa para os repositórios serem linkados.
12- conferi o GitHub
13- criei um arquivo README.md no GitHub
14- usei "git pull" para baixar a atualização do meu repositório remoto para o local
15- usei "git checkout -b conciliar-alteracoes" para criar uma nova branch
16- modifiquei o arquivo README.md nessa branch
17- usei "git status" e constou que o arquivo README.md estava modificado
18- usei o "git add" para adicionar ao staging
19- usei "git commit -m "explicação do README.md"" para commitar a mudança no README.md na branch secundária (salvar no histórico)
20- usei "git push origin conciliar-alteracoes" pra salvar alterações na branch (enviar pro repositório remoto)
21- verifiquei a nova branch no GitHub
22- usei "git checkout master" para voltar pra master
23- usei "git checkout -b "conciliar-alteracoes2" para criar uma nova branch
24- usei "git status" e constou que o arquivo README.md estava modificado
25- usei o "git add" para adicionar ao staging
26- usei "git commit -m "comandos utilizados"" para commitar a mudança no README.md na branch secundária (salvar no histórico)
27- usei "git push origin conciliar-alteracoes2" pra salvar alterações na branch (enviar pro repositório remoto)
20- verifiquei a nova branch no GitHub
28- usei "git merge conciliar-alteracoes" para unir os dois ramos criados ("conciliar-alteracoes" e "conciliar-alteracoes2"
29- houve conflito pois tem coisas escritas nas mesmas linhas, então é preciso aceitar as duas alterações
30- entrei no arquivo README.md e organizei as duas informações
31- usei -git add ."
32- usei "git commit -m "junção das duas informações"
33- usei "git push origin conciliar-alteracoes2"
34- usei "git checkout master"
35- usei "git add ."
36- usei "git commit -m "salvando tudo na master"
37- usei "git push origin master"
38- verifiquei alteração no GitHub
39- fiz outra alteração no README.md na master
40- fiz merge da master com as outras branchs

