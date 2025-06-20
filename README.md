# Lista-S206
Este projeto utiliza o Postman para realizar testes automatizados. O Postman é uma ferramenta que facilita a verificação de casos de teste, garantindo a qualidade e funcionalidade do sistema. Com ele, é possível simular requisições HTTP e validar comportamentos esperados de forma eficiente.
# Sobre os projetos

Verifica cenários:

- Checa todos os projetos
- Checa se um time que não existe da 404
- Cria um projeto com um aluno que não existe
- Cria um projeto com um aluno que existe
- Update no time -> passar o num do grupo como parametro
- Deleta time -> passar o num do grupo como parametro

# Sobre o orientador

Verifica cenários:

- Adiciona um Orientador com sucesso.
- Tenta adicionar um Orientador já existente.
- Mostra todos os Orientadores.
- Busca um Orientador especifico.
- Busca um Orientador que não existe.
- Deleta um Orientador já existente.

# Sobre o Aluno

Verifica cenários:

- Mostra todos os Alunos
- Criar aluno com sucesso.
- Get um Aluno.
- Update um aluno.
- Mostra Projeto do Aluno.
- Deleta um aluno.


# Relatório de Testes

Para gerar o relatório dos testes do Postman automatizados, utilizamos o framework Newman integrado com o reporter htmlextra.

# Instalação do Reporter

Para instalação do reporter, execute o seguinte comando no terminal:

```bash
npm i newman-reporter-htmlextra
```

## Execução dos Testes para Gerar o Relatório

Os testes foram executados utilizando o comando abaixo:

```bash
npx newman run path -e path -r htmlextra
```
