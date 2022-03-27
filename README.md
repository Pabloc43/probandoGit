# probandoGit

    <section class="opiniones">
        <!-- Opiniones -->
        <div class="metaCont">
            <h3>Comentarios de nuestros estudiantes:</h3>

            <ul id="ListaComent" class="listaComent">
                <li>
                    <div class="contenedor">
                        <div class="contenedor-avatar">
                            <img src="images/icon-g2aef2b33f_640.png" alt="Logo usuario">
                        </div>
                        <div class="cajaComentario">
                            <div class="cabezaComent">
                                <h6 class="cabezaComent-nombre">
                                    <a href="#">Agustin Ortiz</a>
                                </h6>
                            </div>
                            <div class="contenidoComent">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit omnis animi et iure
                                laudantium
                                vitae, praesentium optio, sapiente distinctio illo?
                            </div>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="contenedor">
                        <div class="contenedor-avatar">
                            <img src="images/icon-gd086ab5c9_640.png" alt="Logo usuario">
                        </div>
                        <div class="cajaComentario">
                            <div class="cabezaComent">
                                <h6 class="cabezaComent-nombre">
                                    <a href="#">Lorena Rojero</a>
                                </h6>
                            </div>
                            <div class="contenidoComent">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit omnis animi et iure
                                laudantium
                                vitae, praesentium optio, sapiente distinctio illo?
                            </div>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="contenedor">
                        <div class="contenedor-avatar">
                            <img src="images/icon-g2aef2b33f_640.png" alt="Logo usuario">
                        </div>
                        <div class="cajaComentario">
                            <div class="cabezaComent">
                                <h6 class="cabezaComent-nombre">
                                    <a href="#">Agustin Rojero</a>
                                </h6>
                            </div>
                            <div class="contenidoComent">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit omnis animi et iure
                                laudantium
                                vitae, praesentium optio, sapiente distinctio illo?
                            </div>
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </section>


.opiniones{
    display: flex;
    background-color: rgba(255, 147, 147, 0.9);
margin: 220px 0 350px;
}

.contenedor{
    display: flex;
    flex-direction: column;
    align-items: center;
	opacity: 1;
}

 .contenedor div div h6 a{
 	color: #03658c;
 	text-decoration: none;
 }

 .listaComent li{
	 list-style: none;
 }


.metaCont {
	margin: 60px auto 15px;
	width: 768px;
}

.metaCont h3{
	text-align: center;
	font-size: 30px;
	color: #0f4458;
	margin-bottom: 100px;
}

.contenedor-avatar img {
	width: 20%;
}

.cabezaComent {
	background: #FCFCFC;
	padding: 10px 12px;
	border-bottom: 1px solid #E5E5E5;
	overflow: hidden;
	-webkit-border-radius: 4px 4px 0 0;
	-moz-border-radius: 4px 4px 0 0;
	border-radius: 4px 4px 0 0;
}

.cabezaComent-nombre {
	color: #283035;
	font-size: 14px;
	font-weight: 700;
	float: left;
	margin-right: 10px;
}

.contenidoComent {
	background: #FFF;
	padding: 12px;
	font-size: 15px;
	color: #595959;
	-webkit-border-radius: 0 0 4px 4px;
	-moz-border-radius: 0 0 4px 4px;
	border-radius: 0 0 4px 4px;
}

.listaComent li{
	margin-bottom: 40px;
}

.listaComent li:last-child{
	margin-bottom: 160px;
}
