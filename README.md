# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Assinatura do artefato com cosign
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
A pipeline funciona como uma linha de produção, constituída por fases ou etapas, e desta forma todas as áreas atuam na segurança do projeto final, podendo identificar em cada passo uma vulnerabilidade e fazer a devida correção, antes de chegar no processamento final (deploy) e haver perda de tempo tentando identificar em qual das etapas houve a falha de segurança e tendo que retroagir todo o processo e refazê-lo. Ocorre a perda de tempo, dinheiro e o atraso na entrega pode ocasionar o custo de imagem e credibilidade da empresa.
Nesta pipeline, em cada passo, houve a verificaçõ e correção, não prejudicando a esteira da produção final
## URL de Produção
https://segcibgit1.github.io/projeto-devsecop-desafio/
