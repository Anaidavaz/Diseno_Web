        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body>
            <h2>FORMMULARIOS</h2>

            <form action="https://formspree.io/f/mnqwwjon"  method="POST">
                <fieldset>
                  <legend>Información del usuario:</legend>
                  Introducir nombre<br>
                  <input type="text" id="name" name="name"><br>
                  Introducir contraseña<br>
                  <input type="Password" id="pass" name="pass"><br>
                  <label for="lang">Language</label>
                  <select name="languages" id="lang">
                    <option value="javascript">JavaScript</option>
                    <option value="php">PHP</option>
                    <option value="java">Java</option>
                    <option value="golang">Golang</option>
                    <option value="python">Python</option>
                    <option value="c#">C#</option>
                    <option value="C++">C++</option>
                    <option value="erlang">Erlang</option>
                  </select><br><br>
                  <input type="submit" value="Submit">
                </fieldset>
              </form> 

        </body>
        </html>


        EJERCICIO

        </form>
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>formulario</title>
        </head>
        <body>
            <h1>TAQUERIA</h1>
            <h2>menu</h2>
            <h3>tacos</h3>
        <ul> 
            <li>bistec..............................$15</li>
            <li>suadero.............................$15</li>
            <li>longaniza...........................$15</li>
            <li>Tripa...............................$15</li>


        </ul>

        <h3> Especialidades</h3>

        <dl>

        <dt>campechanos...........................$20</dt>
        <dd> combinacion de suadero con loganiza</dd>
        <dt>pastor................................$25</dt>
        <dd>suadero y pastor con piña</dd>
        <dt>Hawaihiana............................$30</dt>
        <dd>con piña y queso</dd>
        </dl>
        <H2>PEDIDOS A DOMICILIO</H2>


        <form action=""method="">
        NOMBRE <Input    type="text" placeholder="Ana contreras"  maxlength="30" minlength="3"

        require> <br>
        TELEFONO <Input type="text" placeholder="5555555555"  maxlength="10" minlength="10"

        require> <br>

        CORREO <Input type="text" placeholder="ana.morales@gmail"  maxlength="30" minlength="30"

        require> <br>

        <p>Para comer en el local o para llevar</p>
        <input type="radio"value="llevar" name="llevar">para llevar <br>
        <input type="radio"value="local" name="llevar">para local
        <p>Si es para llevar; enviar la direccion</p>
        <textarea name="Dirección" id="" cols="30" rows="10" placeholder="calle, número,colonia, delegacion"></textarea> <br>

        elige tus tacos
        <select name="orden 1" id="">
        <option value="bistec">bistec</option>
        <option value="suadero">suadero</option>
        <option value="longaniza">longaniza</option>
        <option value="Tripa">Tripa</option>
        <option value="campachamos">campechanos</option>
        <option value="pastor">pastor</option>
        <option value="Hawiano">Hawaiano</option>
        <input type="number"max="20" min="0">
        <input type="checkbox"value="salsa roja"name= "salsa roja"> salsa roja
        <input type="checkbox"value="salsa verde"name= "salsa verde">salsa verde
        <input type="checkbox"value=" con cebolla"name= "con cebolla">con cebolla


        </select> <br>

        <input type="submit"value="orden lista">

        </FORm>
            <form action="">
               escoge un color <input type="color"> <br>
               password <input type="password"> <br>
               <input type="file"> <br>
               <p>fecha de tu orden</p>
               <input type="date" value="2002-01-01" min="2022-11-19" max="22-12-31">

            </form>



        </body>
        </html>

