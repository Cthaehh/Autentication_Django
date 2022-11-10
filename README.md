<h1 align='center'>Autentication with Django</h1>


<p>Esse é um mini projeto de autenticação do Django com um front-end em HTML e CSS</p>

<hr>

> About

<p>Se você tem alguma sugestão de melhora pro código, sinta-se a vontade (e alias eu lhe peço) para entrar em contato comigo e para conversarmos a respeito. Caso ti interesse para qualquer coisa, fique a vontade para copiar toda e qualquer linha de código desse mini-projetinho</p>
<p><i>Lembrando que os códigos não seguem boas praticas do Django nem do HTML e muito menos do CSS.</i></p>

<h2 align='center'>Views</h2>

<p>As únicas views disponiveis pra acesso são a de login e a de Home com o Menu (por enquanto). Como não tem uma view pra cadastrar um úsuario, se pressume que tenha um úsuario já criado no DB para realizar a autenticação.<p/>

<h3>Login</h3>

<p>
Como dito anteriormente o login precisa de um úsuario cadastrado no db, ele usa o auth que é nativo do Django. Os campos obrigatórios são o username e o password.
Primeiro é feita a validação se o username inputado existe no db, se existe ele trás a senha inputada, converte em uma hash e compara com a hash armazenada no db, se forem do mesmo tamanho, a senha está correta e o login é sucedido, se está correta ele aponta pro úsuario que o login não foi sucedido por que a senha está incorreta. Agora se o username não existe ele não passa pra faze de validação de senha e aponta pro úsuario que o nome de úsuario inputado não existe.
</p>

<h3>Login</h3>
