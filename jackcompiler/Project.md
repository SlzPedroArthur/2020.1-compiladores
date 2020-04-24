
### Usando a API

Um pseudocódigo que mostra como poderiamos usar a API JackTokenizer.

```
tknz = new JackTokenizer ("Prog.jack")
tknz.advance();
print "<tokens>"
while tknz.hasMoreTokens() {
	tokenClass = tipo do token corrente
	print "<" + tokenClass + ">"
	print token corrent
	print "</" + tokenClass + ">"
	print newline
	tknz.advance()
}
print "</tokens>"
```

***

### Projeto

Cada aluno deve desenvolver um analisador léxico para a linguagem Jack. Para isso, pode-se usar qualquer linguagem de alto nível (Rust).
 
O analisador léxico deve reconhecer os tokens da linguagem Jack. O analisador deve ser implementado de acordo com a API proposta aqui, podendo fazer algumas adaptações para se adequar melhor a linguagem utilizada. Lembre-se que esta API será usado pelo analisador sintático. 

Cada aluno deverá criar um repositório no github ou gitlab com o nome jackcompiler. Nesse momento o projeto deverá ter no mínimo uma classe JackTokenizer, e uma outra chamada JackCompiler. Essa última será o "ponto de partida" do nosso programa. 

No envio da atividade, deverá ser enviado o código e o link para o github ou gitlab.

O link para o github deverá ser enviado no grupo da disciplina no whatsapp. 

Qualquer dúvida, poderá ser dirigida no grupo do whatsapp. Por isso é importante manter o codigo no github ou gitlab.

Para testar o analisador, utiliza o seguinte [código em Jack](../projetos/01/Main.jack), que deverá resultar neste [arquivo XML](../projetos/01/Main.xml).
