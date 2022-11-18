link do tutorial de como instalar o backup wordpress: https://www.youtube.com/watch?v=tNR3hl80YmI&ab_channel=WP24Horas
usuário para logar no sistema: admin
senha: admin


OBS: 	Em wp-contents/themes/graduate/functions.php você ira encontrar uma função chamada registerThemerAssets(),
esta função tem o objetivo de registrar os documentos JavaScripts e de CSS de maneira correta para que sejam acessiveis
em todo o wordpress. A baixo desta função se encontra a chamada hook desta função.

	Nos templates template_book.php e view_template.php existe um comentário no inicio do documento,
 exemplo: "Template Name: Book Registration Form" este comentário é responsável pelo nome que o documento terá
dentro do wordpress na hora de selecionar o modelo da página, é importante que ele seja único
e siga o modelo -> "Template Name: XXXXXXXXX"