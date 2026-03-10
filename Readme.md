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
                <p>Portfólio de projetos e experiências em infraestrutura de TI, automação e sistemas críticos.</p> 
            </header>             
            <nav id="nav"> 
                <ul> 
                    <li><a href="#one" class="active">Resumo</a></li>                     
                    <li><a href="#infrastructure">Infraestrutura & NOC</a></li>                     
                    <li><a href="#automation">Automação & IoT</a></li>                     
                    <li><a href="#telecom">Telecom & Segurança</a></li>                     
                    <li><a href="#media">Cloud & Media</a></li>                     
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
                            <p>Exposição de competências técnicas através de casos de uso reais.</p> 
                        </header>                         
                        <p>Esta lista detalha projetos implementados para sanar necessidades críticas em diversas empresas, unindo monitoramento, alta disponibilidade e automação personalizada.</p> 
                    </div>                     
                </section>                 

                <section id="infrastructure"> 
                    <div class="container"> 
                        <h3>Infraestrutura & NOC</h3> 
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>NOC - Central de Monitoramento</h4>
                                    <p>Integração de recursos de TI com dashboards modernos e alertas via Telegram/E-mail.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-chart-line">Grafana, Zabbix</li>
                                        <li class="icon solid fa-database">MySQL, JSON</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Rancher Farm</h4>
                                    <p>Gestão e orquestramento de containers em farm redundante com alta disponibilidade.</p>
                                    <ul class="feature-icons">
                                        <li class="icon brands fa-docker">Docker, K8s</li>
                                        <li class="icon solid fa-server">Rancher, Suse Linux</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Veeam - Backup & Imutabilidade</h4>
                                    <p>Implementação de backup em volumes iSCSI/NFS, Tapes, imutabilidade e políticas de retenção.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-shield-alt">Imutabilidade</li>
                                        <li class="icon solid fa-save">iSCSI, NFS, Tapes</li>
                                    </ul>
                                </div>
                            </article>
                        </div>
                    </div>                     
                </section>                 

                <section id="automation"> 
                    <div class="container"> 
                        <h3>Automação & IoT</h3> 
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>DASP - Acesso Seguro Pendrives</h4>
                                    <p>Central unificada de controle e formatação de pendrives (xFAT, vFAT) via Raspberry.</p>
                                    <ul class="feature-icons">
                                        <li class="icon brands fa-linux">Linux, Raspberry</li>
                                        <li class="icon solid fa-key">LDAP, AD, Python</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Telemetria & Termometria</h4>
                                    <p>Captura de dados de Nobreaks (Nuts/SNMP) e sensores de temperatura em Datacenters.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-bolt">Nuts, UPS, SNMP</li>
                                        <li class="icon solid fa-thermometer-half">IoT, WebServers</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Sistema de Pesagem Rodoviária</h4>
                                    <p>Coleta via RS-232 com filtros Regex para garantir a integridade dos dados de balanças.</p>
                                    <ul class="feature-icons">
                                        <li class="icon fa-brands fa-raspberry-pi">IoT, API</li>
                                        <li class="icon solid fa-code">Python, Stream Data</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Sinalização Interna IoT</h4>
                                    <p>Dispositivos para exibição de campanhas, previsão do tempo e integração Instagram.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-tv">Chromium, API</li>
                                        <li class="icon brands fa-instagram">Instagram, Python</li>
                                    </ul>
                                </div>
                            </article>
                        </div>
                    </div>                     
                </section>                 

                <section id="telecom"> 
                    <div class="container"> 
                        <h3>Telecomunicações & Segurança</h3> 
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>PABX Asterisk & WhatsApp</h4>
                                    <p>Central SIP com URAs, campanhas e implementação de fluxos Omnichannel via Meta API.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-phone">SIP, Asterisk</li>
                                        <li class="icon brands fa-whatsapp">Meta API, Omnichanel</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Segurança de Rede & Firewall</h4>
                                    <p>Implementação de Cloudflare Tunnels e Captive Portal (OpnSense) integrado ao AD.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-user-shield">Cloudflare, Docker</li>
                                        <li class="icon solid fa-network-wired">OpnSense, API</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>SafeVault & FAV</h4>
                                    <p>Cofre de senhas e portal de favoritos setorizado com foco em conformidade LGPD.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-lock">SafeVault, PHP</li>
                                        <li class="icon solid fa-folder">MySQL, JS, LGPD</li>
                                    </ul>
                                </div>
                            </article>
                        </div>
                    </div>                     
                </section>

                <section id="media">
                    <div class="container">
                        <h3>Cloud Storage & Media Streaming</h3>
                        <div class="features">
                            <article>
                                <div class="inner">
                                    <h4>Cloud Storage & NVR Virtual</h4>
                                    <p>Nextcloud para arquivos e Frigate para NVR com captura RTSP e máscaras de área.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-cloud">Nextcloud, Docker</li>
                                        <li class="icon solid fa-video">Frigate, RTSP</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Streaming de Áudio & Vídeo</h4>
                                    <p>Servidores Jellyfin (GPU Passthrough) e Icecast para audio marketing corporativo.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-film">Jellyfin, Codec</li>
                                        <li class="icon solid fa-broadcast-tower">Icecast, MP3</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Implementação Pulsus MDM</h4>
                                    <p>Gestão de endpoints Android, rastreamento GPS e políticas de uso gerenciais.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-mobile-alt">MDM, Android</li>
                                        <li class="icon solid fa-map-marker-alt">GPS, API</li>
                                    </ul>
                                </div>
                            </article>
                        </div>
                    </div>
                </section>

                <section id="contact"> 
                    <div class="container"> 
                        <h3>Contato</h3> 
                        <form method="post" action="#"> 
                            <div class="row gtr-uniform"> 
                                <div class="col-6 col-12-xsmall"><input type="text" name="name" id="name" placeholder="Nome"/></div>                                 
                                <div class="col-6 col-12-xsmall"><input type="email" name="email" id="email" placeholder="Email"/></div>                                 
                                <div class="col-12"><textarea name="message" id="message" placeholder="Mensagem" rows="6"></textarea></div>                                 
                                <div class="col-12"> 
                                    <ul class="actions"> 
                                        <li><input type="submit" class="primary" value="Enviar Mensagem"/></li>                                         
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


