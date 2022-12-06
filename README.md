# Cadastrar alunos com programação orientada a objetos.
Criando classes e atributos de objetos:

Fazer as informações captadas por input aparecerem na tela:

function quandoClicarNoBotaoCadastrar() {
  let result = new Aluno(inNome.value, inIdade.value, inTurma.value)
  document.write(`<h2>${result.nome}</h2>`)
  document.write(`<div>${result.idade}</div>`)
  document.write(`<div>${result.turma}</div>`)
}
