# Lista-S206
Este projeto utiliza o Postman para realizar testes automatizados. O Postman é uma ferramenta que facilita a verificação de casos de teste, garantindo a qualidade e funcionalidade do sistema. Com ele, é possível simular requisições HTTP e validar comportamentos esperados de forma eficiente.
# Sobre os projetos

Verifica cenários:

- Criar um projeto com aluno não cadastrado.
- Criar um projeto só com orientador.
- Criar um projeto com sucesso.
- Criar um projeto que ja existe.
- Criar um projeto e deletar.
- Criar um projeto, deletar intengrantes e salvar projeto.

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

- Criar aluno com sucesso.
- Criar aluno com sucesso, faz logout e loga como aluno.
- Tenta criar aluno sem usuario.
- Tenta criar aluno sem senha.
- Tenta criar aluno sem email.
- Tenta criar aluno sem passar nada.


# Relatório de Testes

Para gerar o relatório dos testes automatizados, utilizamos o framework Newman integrado com o reporter newman htmlextra.

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
