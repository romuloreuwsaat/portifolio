{% include head.html %}
<html>
    <head>        
        <meta charset="utf-8"/> 
        <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no"/> 
        <link rel="stylesheet" href="/assets/css/main.css"/> 
    </head>     
 	<body class="is-preload"> 
        <section id="header"> 
            <header> <span class="image avatar"><img src="/images/avatar.jpg" alt=""/></span> 
                <h1 id="logo"><a href="#">Rômulo Reuwsaat</a></h1> 
                <p>Uma breve listagem de projetos relevantes e experiências guiadas pelo meu conhecimento.</p> 
            </header>             
            <nav id="nav"> 
                <ul> 
                    <li><a href="#one" class="active">Resumo</a></li>                     
                    <li><a href="#two">Infraestrutura & NOC</a></li>                     
                    <li><a href="#three">Automação & IoT</a></li>                     
                    <li><a href="#four">Telecom & Segurança</a></li>                     
                    <li><a href="#contact">Contato</a></li>                     
                </ul>                 
            </nav>             
            <footer> 
                <ul class="icons"> 
                    <li><a href="#" class="icon brands fa-github"><span class="label">Github</span></a></li> 
                    <li><a href="#" class="icon solid fa-envelope"><span class="label">Email</span></a></li> 
                </ul>                 
            </footer>             
        </section>         

        <div id="wrapper"> 
            <div id="main"> 

                <section id="one"> 
                    <div class="image main" data-position="center"> 
                        <img src="images/banner.jpg" alt=""/> 
                    </div>                     
                    <div class="container"> 
                        <header class="major"> 
                            <h2>Portfólio</h2> 
                            <p>Explicando sobre alguns dos projetos que domino</p> 
                        </header>                         
                        <p>Esta lista é dedicada a descrever experiências por meio de casos de uso de necessidades reconhecidas em diversas empresas que trabalhei, os quais usarei para expor minhas competências e conhecimento técnico em prática.</p> 
                    </div>                     
                </section>                 

                <section id="two"> 
                    <div class="container"> 
                        <h3>Infraestrutura, Cloud & Monitoramento</h3> 
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>NOC & Observabilidade</h4>
                                    <p>Implementação de dashboards <b>Grafana + Zabbix</b> para monitoramento em tempo real.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Backup & Continuidade (Veeam)</h4>
                                    <p>Implementação de <b>Veeam</b> com volumes NFS, imutabilidade e gestão de Tapes.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Virtualização & Containers</h4>
                                    <p>Gestão com <b>Rancher</b> para orquestração e <b>Nextcloud</b> para storage privado.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Storage & NVR</h4>
                                    <p>Servidor de NVR virtualizado com <b>Frigate</b> e armazenamento via RTSP.</p>
                                </div>
                            </article>
                        </div>
                    </div>                     
                </section>                 

                <section id="three"> 
                    <div class="container"> 
                        <h3>Automação & IoT</h3> 
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>SBC & Termometria</h4>
                                    <p>Coleta de temperaturas e status web usando <b>Raspberry Pi</b> e sensores.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Automações PowerShell</h4>
                                    <p>Gestão de agentes, portais web e personalização de wallpapers corporativos.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Sistemas de Pesagem</h4>
                                    <p>Integração e coleta de peso em balanças rodoviárias para logística.</p>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Mobilidade & MDM</h4>
                                    <p>Implementação de gestão de dispositivos móveis com <b>Pulsus MDM</b>.</p>
                                </div>
                            </article>
                        </div>
                    </div>                     
                </section>                 

                <section id="four">
                    <div class="container">
                        <h3>Telecomunicações, Segurança & Media</h3>
                        <p>Soluções críticas de comunicação e proteção de dados.</p>
                        <ul class="feature-icons">
                            <li class="icon solid fa-phone">PABX Asterisk & SIP</li>
                            <li class="icon solid fa-shield-alt">Firewall & Captive Portal</li>
                            <li class="icon solid fa-lock">SafeVault & Segurança Web</li>
                            <li class="icon solid fa-broadcast-tower">Icecast Audio Streaming</li>
                            <li class="icon brands fa-whatsapp">WhatsApp Corporativo</li>
                            <li class="icon solid fa-tv">Sinalização Interna & Web</li>
                        </ul>
                    </div>
                </section>

                <section id="contact"> 
                    <div class="container"> 
                        <h3>Contact Me</h3> 
                        <form method="post" action="#"> 
                            <div class="row gtr-uniform"> 
                                <div class="col-6 col-12-xsmall"><input type="text" name="name" id="name" placeholder="Name"/></div>                                 
                                <div class="col-6 col-12-xsmall"><input type="email" name="email" id="email" placeholder="Email"/></div>                                 
                                <div class="col-12"><textarea name="message" id="message" placeholder="Message" rows="6"></textarea></div>                                 
                                <div class="col-12"> 
                                    <ul class="actions"> 
                                        <li><input type="submit" class="primary" value="Send Message"/></li>                                         
                                    </ul>                                     
                                </div>                                 
                            </div>                             
                        </form>                         
                    </div>                     
                </section>                 

            </div>             

            <section id="footer"> 
                <div class="container"> 
                    <ul class="copyright"> 
                        <li>&copy; Rômulo Reuwsaat. All rights reserved.</li>
                        <li>Design: <a href="http://html5up.net">HTML5 UP</a></li>                         
                    </ul>                     
                </div>                 
            </section>             
        </div>         

        <script src="https://rr.meineautomatichaus.de/assets/js/jquery.min.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/jquery.scrollex.min.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/jquery.scrolly.min.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/browser.min.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/breakpoints.min.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/util.js"></script>         
        <script src="https://rr.meineautomatichaus.de/assets/js/main.js"></script>         
    </body>     
</html>
