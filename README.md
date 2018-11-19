# Projeto para comercializar produtos organicos. #
# Em fase de desenvolvimento #

O projeto teve inicio no ano de 2018 e foi criado pelos desenvolvedores: 
- [Moises Reichert](https://www.facebook.com/motz182)

# Orientações para os desenvolvedores #

## Convenção de commits ##

### Deve ser utilizado o seguinte padrão para commits: #
 
    tipo(contexto): mensagem
 
### Onde: ###

- **Tipo:** 

    - feat: uma nova feature. 
    - fix: uma correção. 
    - docs: alteração apenas em documentação. 
    - style: alterações que não afetam código (espaço em branco, formatação, etc). 
    - refactor: melhoria específica de código, que não tem como motivo correção ou adicionar nada. 
    - perf: melhorias de performance 
    - test: correção ou adição de testes. 
    - chore: alterações diversar envolvendo libs, sdks, etc.
    
- **Contexto:**
    
    - Em qual parte do software foi aplicado a alteração (ex: login, account, invoices, checkout). Caso não se aplique, pode utilizar *. 
  
- **Mensagem:**
    - Mensagem rápida sobre o que foi realizado. 
 
 
### Exemplo de commit: ###

    fix(cadUsuario): corrigindo erro quando email é nulo 
