# cliente
<div id="app"></div>

<head>
    <meta charset="UTF-8" />
    <title></title>
    <link href='https://fonts.googleapis.com/css?family=Open Sans' rel='stylesheet'>
    <link rel="stylesheet" type="text/css" href="estilo.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
</head>

<body onload="carregar()">
    <header>
        <div class="barra">
            <i class="material-icons mysize" id="info">info</i>
            <h1>Cadastro de Clientes</h1>
            <i class="material-icons mysize2" id="voltar">arrow_back</i>
        </div>
    </header>
<img src="https://senaigoias.com.br/repositoriosites/repositorio/senai/editor/Image/vestibular20/imagens_curso_desenvolvimento_sistema.jpg" alt="some text" width=600 height=>
    <main>
        <div class="home">  
            <form>
                <div class="input-container">
                  <div class="container-pesquisar">
                    <i class="material-icons" id="search">search</i>
                    <input id="pesquisar" type="text" placeholder="Para pesquisar digite aqui"/>
                  </div>
                    <ul id="load">
                            <li></li>
                    </ul>
                </div>
            </form>
            <div class="float">
                    <a class="material-icons" id="add">add_circle</a>
            </div>
        </div>
           
        <id="container-cadastro" class="cadastro">
          <form>
                <div class="input-container2">
                    <label for="nome">Nome</label>
                    <input type="text" placeholder="Digite o nome do cliente" id="nome">
                </div>
                  
                <div class="input-container2">
                    <label for="cpf">CPF</label>
                    <input type="number" placeholder="Digite o CPF do cliente" id="cpf">
                </div>
                    
                <div class="input-container2">
                    <div class="styled-select">
                    <label for="sexo">Sexo</label>
                    <select name="" id="sexo" >
                        <option value="" disabled selected>Selecione o sexo</option>
                        <option value="femi">Feminino</option>
                        <option value="masc">Masculino</option>
                        <option value="mt">Outro</option>
                    </select>
                    </div>
                </div>
                    
                <div class="input-container2">
                    <label for="email">E-mail</label>
                    <input type="email" placeholder="Digite o e-mail do cliente" id="email">
                </div>

                <div class="input-container2">
                    <label for="telefone">Telefone</label>
                    <input type="phone" placeholder="Digite o Telefone do cliente" id="telefone">
                </div>
                  
                <div class="input-container2">
                    <label for="nascimento">Data de Nascimento</label>
                    <input type="date" placeholder="Digite a data de nascimento" id="nascimento">
                </div>

                <div class="input-container2">
                    <div class="styled-select">
                    <label for="estado">Estado</label>
                    <select name="" id="estado" >
                        <option value="" disabled selected>Selecione o estado</option>
                        <option value="ac">AC</option>
                        <option value="al">AL</option>
                        <option value="ap">AP</option>
                        <option value="am">AM</option>
                        <option value="ba">BA</option>
                        <option value="ce">CE</option>
                        <option value="df">DF</option>
                        <option value="es">ES</option>
                        <option value="go">GO</option>
                        <option value="ma">MA</option>
                        <option value="mt">MT</option>
                        <option value="ms">MS</option>
                        <option value="mg">MG</option>
                        <option value="pa">PA</option>
                        <option value="pb">PB</option>
                        <option value="pr">PR</option>
                        <option value="pe">PE</option>
                        <option value="pi">PI</option>
                        <option value="rj">RJ</option>
                        <option value="rn">RN</option>
                        <option value="rs">RS</option>
                        <option value="ro">RO</option>
                        <option value="rr">RR</option>
                        <option value="sc">SC</option>
                        <option value="sp">SP</option>
                        <option value="se">SE</option>
                        <option value="to">TO</option>
                    </select>
                    </div>
                </div>
          
                <div class="input-container2">
                    <label for="nome">Cidade</label>
                    <input type="text" placeholder="Digite o nome do cidade" id="cidade">
                </div>
                 <div class="input-container2">
                    <label for="nome">Pais</label>
                    <input type="text" placeholder="Digite o nome do pais" id="pais">
                </div>
                 <div class="input-container2">
                    <label for="nome">CNPJ</label>
                    <input type="text" placeholder="Digite o cnpj" id="cnpj">
                </div>
                
                 <div class="input-container2">
                    <label for="nome">Empresa</label>
                    <input type="text" placeholder="Digite o nome do empresa" id="empresa">
                </div>
          </form>
          
            <div class="button-container-button">
                <i class="btn-salvar" aria-hidden="true"></i>
                <input type="button" value="Salvar" id="btnsalvar">
                <i class="btn-remover" aria-hidden="true"></i>
                <input type="button" value="Remover" id="btnremover">
            </div>
              
        </div>
    </main>

<script type="text/javascript" src="javascript.js"></script>  
<iframe name="imc" width="385" height="630" src="https://indicedemassacorporal.com/calculadora-imc.html" scrolling="no" frameborder="1" marginwidth="0" marginheight="0"></iframe>
 
