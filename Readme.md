{% include head.html %}
<html lang="pt-br">
<head>        
    <meta charset="utf-8"/> 
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no"/> 
    <link rel="stylesheet" href="/assets/css/main.css"/> 
    <title>Portfólio - Rômulo Reuwsaat</title>
</head>     
<body class="is-preload"> 

    <section id="header"> 
        <header> 
            <span class="image avatar"><img src="/images/avatar.jpg" alt="Avatar"/></span> 
            <h1 id="logo"><a href="#">Rômulo Reuwsaat</a></h1> 
            <p>Portifólio de projetos e experiências em infraestrutura de TI, automação e sistemas críticos.</p> 
        </header>               
        <nav id="nav"> 
            <ul> 
                <li><a href="#one" class="active">Resumo</a></li>                       
                <li><a href="#infrastructure">Infraestrutura & NOC</a></li>                       
                <li><a href="#automation">Automação & IoT</a></li>                       
                <li><a href="#telecom">Telecom & Segurança</a></li>
                <li><a href="#media">Cloud & Media</a></li>  
                <li><a href="#print">Integrações em Impressão</a></li> 
                <li><a href="#contact">Contato</a></li>                       
            </ul>                   
        </nav>              
        <footer> 
            <ul class="icons"> 
                <li><a href="#" class="icon brands fa-linkedin"><span class="label">Linkedin</span></a></li> 
                <li><a href="#" class="icon solid fa-envelope"><span class="label">Email</span></a></li> 
            </ul>                   
        </footer>              
    </section>          

    <div id="wrapper"> 
        <div id="main"> 

            <section id="one"> 
                <div class="image main" data-position="center"> 
                    <img src="images/banner.jpg" alt="Banner"/> 
                </div>                         
                <div class="container"> 
                    <header class="major"> 
                        <h2>Portifólio</h2> 
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
                                <p>Implementação de NOC, integração de recursos de TI com dashboards modernos e alertas via Telegram/E-mail.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-chart-line">Grafana, Zabbix</li>
                                    <li class="icon solid fa-database">MySQL, JSON</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Hypervisors</h4>
                                <p>Instalação, manutenção e atualização de hypervisors como ESXi, Xen, KVM (Proxmox) e Hyper-V.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-microchip">Servers, Linux, Microsoft</li>
                                    <li class="icon solid fa-cubes">Hypervisors, KVM, ESXi</li>
                                </ul>
                            </div>
                        </article>
                        <article> <div class="inner">
                                <h4>Rancher Farm</h4>
                                <p>Implementação de ecossistema Rancher, gestão e orquestramento de containers em farm redundante.</p>
                                <ul class="feature-icons">
                                    <li class="icon brands fa-docker">Docker, K8s</li>
                                    <li class="icon solid fa-server">Rancher, Suse Linux</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Veeam - Backup & Imutabilidade</h4>
                                <p>Implementação de solução de backup em volumes iSCSI/NFS e Tape Library.</p>
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
                                <p>Controle e formatação de pendrives via Raspberry, isolada da infraestrutura interna.</p>
                                <ul class="feature-icons">
                                    <li class="icon brands fa-linux">Linux, Raspberry</li>
                                    <li class="icon solid fa-key">LDAP, AD, Python</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Telemetria & Termometria</h4>
                                <p>Captura de dados de Nobreaks (Nuts/SNMP) e sensores de temperatura.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-bolt">Nuts, UPS, SNMP</li>
                                    <li class="icon solid fa-thermometer-half">IoT, WebServers</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Sistema de Pesagem Rodoviária</h4>
                                <p>Coleta via RS-232 utilizando filtros regex em Python para garantir integridade dos dados.</p>
                                <ul class="feature-icons">
                                    <li class="icon brands fa-raspberry-pi">IoT, API</li>
                                    <li class="icon solid fa-code">Python, Stream Data</li>
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
                                <p>Central SIP com URAs e gestão de Meta API para WhatsApp.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-phone">SIP, Asterisk</li>
                                    <li class="icon brands fa-whatsapp">Meta API</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Segurança de Rede & Firewall</h4>
                                <p>Cloudflare Tunnels e Captive Portal (OpnSense) integrado ao AD.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-user-shield">Cloudflare, Docker</li>
                                    <li class="icon solid fa-network-wired">OpnSense, API</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>SafeVault & FAV</h4>
                                <p>Cofre de senhas e portal de favoritos com foco em LGPD.</p>
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
                                <p>Nextcloud e Frigate NVR com captura RTSP e notificações.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-cloud">Nextcloud, Docker</li>
                                    <li class="icon solid fa-video">Frigate, RTSP</li>
                                </ul>
                            </div>
                        </article>
                        <article>
                            <div class="inner">
                                <h4>Streaming de Áudio & Vídeo</h4>
                                <p>Jellyfin (GPU Passthrough) e servidor Icecast.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-film">Jellyfin, Codec</li>
                                    <li class="icon solid fa-broadcast-tower">Icecast, MP3</li>
                                </ul>
                            </div>
                        </article>
                    </div>
                </div>
            </section>

 <section id="print">
    <div class="container">
        <h3>Printer Services</h3>
        <div class="features">
            <article>
                <div class="inner">
                    <h4>SAP + MS Active Directory Pool Integration</h4>
                    <p>Integração de identificação de impressoras co-relacionando esturuta em AD para entrega de jobs.</p>
                    <ul class="feature-icons">
                        <li class="icon solid fa-print">CUPS</li>
                        <li class="icon solid fa-sitemap">MS-Active Directory</li>
                        <li class="icon solid fa-database">SAP 4 HANA & FIORI</li>
                    </ul>
                </div>
            </article>
        </div>
    </div>
</section>       

            <section id="contact"> 
                <div class="container"> 
                    <h3>Contato</h3> 
                    <form id="contact-form"> 
                        <div class="row gtr-uniform"> 
                            <div class="col-6 col-12-xsmall">
                                <input type="text" name="from_name" id="name" placeholder="Nome" required/>
                            </div>                                     
                            <div class="col-6 col-12-xsmall">
                                <input type="email" name="reply_to" id="email" placeholder="Email" required/>
                            </div>                                     
                            <div class="col-12">
                                <textarea name="message" id="message" placeholder="Mensagem" rows="6" required></textarea>
                            </div>                                     
                            <div class="col-12"> 
                                <ul class="actions"> 
                                    <li><input type="submit" id="button" class="primary" value="Enviar Mensagem"/></li>                                             
                                </ul>                                         
                            </div>                                     
                        </div>                                
                    </form>                          
                </div>                       
            </section>                   

        </div> <section id="footer"> 
            <div class="container"> 
                <ul class="copyright"> 
                    <li>&copy; Rômulo Reuwsaat. All rights reserved.</li> 
                    <li>
                        <script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script>
                        <script type='text/javascript'>
                            kofiwidget2.init('Fui útil? Pague um café!', '#72a4f2', 'S6S8PMDYA');
                            kofiwidget2.draw();
                        </script>
                    </li>                          
                </ul>                       
            </div>                   
        </section>              
    </div> <script src="https://rr.meineautomatichaus.de/assets/js/jquery.min.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/jquery.scrollex.min.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/jquery.scrolly.min.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/browser.min.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/breakpoints.min.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/util.js"></script> 
    <script src="https://rr.meineautomatichaus.de/assets/js/main.js"></script> 
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    
    <script type="text/javascript">
        (function() {
            emailjs.init("VlmQWkmDNbSyBtIbz");
        })();

        const btn = document.getElementById('button');

        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            btn.value = 'Enviando...';

            const serviceID = 'service_p7twbbq';
            const templateID = 'template_syb7ork';

            emailjs.sendForm(serviceID, templateID, this)
            .then(() => {
                btn.value = 'Enviar Mensagem';
                alert('Mensagem enviada com sucesso!');
                this.reset();
            }, (err) => {
                btn.value = 'Enviar Mensagem';
                alert('Erro ao enviar: ' + JSON.stringify(err));
            });
        });
    </script>
</body>
</html>
