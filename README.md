<h1>library-localStorage</h1>

<h2>COMO INICIAR:</h2>
   <p>Para iniciar, basta criar uma instância de Storage passando ao constructor um nome (no formato string) que será utilizado para nomear o slot de memória criado.</p>
       <p>EXEMPLO: <code>var armazenamento = new Storage("nome")</code> </p>

<h2>COMO USAR:</h2>
       <p>Esta biblioteca foi criada com o intuito de simplificar o uso do localStorage adicionando diversos métodos para facilitar o armazenamento local de dados.</p>

       Após a criação da instância, você poderá utilizar os seguintes métodos para modificar o armazenamento:

<p>.set(valor) - Substitui os dados armazenados pelo novo valor passado ao método.</p>


<p>.add(valor) - adiciona o valor passado ao método ao final da lista de valores já armazenados. </p>


<p>.getElements() - Retorna um Array com todos os valores armazenados.</p>


<p>.getIndexOf(valor) - retorna o index do primeiro valor da memória correspondente ao valor passado (retonrna -1 caso não haja um valor correspondente).</p>


<p>.getElementByIndex(valor) - retorna o elemento correspondente ao index passado ao método. </p>


<p>.removeAllChilds(valor) - Remove do armazenamento todos os valores correspondentes ao valor fornecido ao método. </p>


<p>.removeFirstChild(valor) - Remove da memória o primeiro valor correspondente ao valor passado.</p>


<p>.removeChildByIndex(index) - Recebe um valor numérico e remove o valor com index correspondente da memória (retorna -1 caso não haja um valor com o index passado).</p>

