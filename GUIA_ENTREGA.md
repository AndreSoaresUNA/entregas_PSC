# Entrega pelo GitHub — sem convite de colaborador
Repositório da turma: https://github.com/AndreSoaresUNA/entregas_PSC

## Caminho recomendado
1. Entre na sua conta GitHub. Abra o link da turma e clique **Fork → Create fork**.
2. Na SUA cópia, clique Code e copie a URL HTTPS.
3. No VS Code, use Git: Clone ou o terminal (troque SEU_USUARIO):
```powershell
git clone https://github.com/SEU_USUARIO/entregas_PSC.git
cd entregas_PSC
git switch -c aula2-SEU_USUARIO
```
4. Crie entregas/aula2/SEU_USUARIO. Coloque ali Desafio01.java, as demais missões e README.md. Nunca altere a pasta de um colega.
5. Teste cada arquivo dentro da sua pasta:
```powershell
javac -encoding UTF-8 Desafio01.java
java Desafio01
```
6. Volte à raiz do clone e execute (troque SEU_USUARIO):
```powershell
git add entregas/aula2/SEU_USUARIO
git status
git commit -m "Entrega Aula 2 - SEU_USUARIO"
git push -u origin aula2-SEU_USUARIO
```
7. No GitHub, abra seu fork, clique **Compare & pull request** (ou Contribute → Open pull request). Base: AndreSoaresUNA/entregas_PSC, main. Origem: seu fork, aula2-SEU_USUARIO.
8. Título: Aula 2 — SEU_USUARIO. Descreva missões e testes. Clique Create pull request e copie o link da entrega.

**A entrega é o pull request aberto**, mesmo antes de o professor aceitar. Push no fork sozinho não conclui a entrega.
Para corrigir, faça novo commit e push na mesma branch: o PR atualiza automaticamente.

## Identidade e autenticação
Se o commit pedir identidade:
```powershell
git config user.name "Seu nome"
git config user.email "Seu email de commit do GitHub"
```
Pode usar o endereço noreply indicado em GitHub → Settings → Emails. O email do commit pode ficar público.
Na autenticação, use o fluxo do navegador oferecido pelo Git/VS Code. Sua senha comum do GitHub não funciona como senha de push HTTPS. Não cole tokens no código ou no README.

## Erros frequentes
- 403 / permission denied: confira se origin aponta para SEU fork: git remote -v.
- “not a git repository”: entre na pasta clonada.
- “nothing to commit”: salve os arquivos e confira a pasta adicionada.
- Pasta pronta mas sem Git: clone primeiro e copie suas soluções para dentro.
- Não use force push para resolver problemas nesta atividade; peça ajuda.

## Alternativa sem terminal Git
No seu fork, use Add file → Upload files. Abra a pasta entregas/aula2/SEU_USUARIO antes do upload (crie primeiro um README nessa pasta via Add file → Create new file). Envie só .java e README, confirme o commit e abra Contribute → Open pull request.
Repositório público torna seu código e usuário visíveis. Não inclua matrícula, telefone, documento ou notas reais. As notas dos desafios são fictícias.

