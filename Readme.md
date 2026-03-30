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
                <p>Portifólio de projetos e experiências em infraestrutura de TI, automação e sistemas críticos.</p> 
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
                    <li><a href="#" class="icon brands fa-linkedin"><span class="label">Linkedin</span></a></li> 
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
                                    <p>Instalação, manutenção e atualização de hypervisors em servidores em projetos de datacenters como ESXi(VMWare/Broadcom), Xen(Legado Citrix e Xenserver), KVM(Proxmox e RHEL), Type2(VirtualBox) e Hypver-V(Microsoft).</p>
                                    <ul class="feature-icons">
                                        <li class="icon brands fa-server">Servers, Linux, Microsoft</li>
                                        <li class="icon solid fa-cubes">Hypervisors, KVM, ESXi, Type2, Xen</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                            <article>
                                <div class="inner">
                                    <h4>Rancher Farm</h4>
                                    <p>Implementação de ecossistema Rancher, gestão e orquestramento de containers em farm redundante com alta disponibilidade.</p>
                                    <ul class="feature-icons">
                                        <li class="icon brands fa-docker">Docker, K8s</li>
                                        <li class="icon solid fa-server">Rancher, Suse Linux</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Veeam - Backup & Imutabilidade</h4>
                                    <p>Implementação de solução de backup em volumes iSCSI/NFS(imutabilidade) e Tape Library com definições das políticas de retenção.</p>
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
                                    <p>Central unificada de controle e formatação de pendrives (xFAT, vFAT) via Raspberry, solução isolada da infraestrutura de rede interna para fins de segurança e prevenção de infecções.</p>
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
                                    <p>Desenvolvimento de solução de coleta via RS-232 de stream de dados, utilizando avançados filtros regex em python para garantir a integridade, estabilidade e disponibilidade do serviço de coleta de peso de cargas.</p>
                                    <ul class="feature-icons">
                                        <li class="icon brands fa-raspberry-pi">IoT, API</li>
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
                                    <p>Implementação de central SIP com URAs, campanhas e inteligência para atendimento direcionado de chamadas, gestão de solução junto à Meta API de WhatsApp vinculado a DDRs setorizados, manutenção de agentes e de fluxos de atendimento.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-phone">SIP, Asterisk</li>
                                        <li class="icon brands fa-whatsapp">Meta API, Omnichanel</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Segurança de Rede & Firewall</h4>
                                    <p>Implementação de Cloudflare Tunnels para segurança de publicações web, implementação de firewall para segurança e plataforma privada de captive portal (OpnSense) integrado ao AD.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-user-shield">Cloudflare, Docker</li>
                                        <li class="icon solid fa-network-wired">OpnSense, API</li>
                                    </ul>
                                </div>
                            </article>
							<article>
                            <div class="inner">
                                <h4>Mail Server & WebOffice Apps</h4>
                                <p>Implementação de servidor de email, com filtros de conteúdo, white/blacklist, gestão de dominio(registros, chaves, autenticação com plataformas de segurança), antispam e aplicações web(calendário, editores de texto e planilhas) opensource.</p>
                                <ul class="feature-icons">
                                    <li class="icon solid fa-cloud">DNS, Domains, Web</li>
                                    <li class="icon solid fa-envelope">iRedMail, SMTP, IMAP, POP</li>
                                </ul>
                            </div>
                        </article>
                            <article>
                                <div class="inner">
                                    <h4>SafeVault & FAV</h4>
                                    <p>Cofre de senhas e portal de favoritos setorizado com foco em conformidade LGPD com autenticação integrada ao AD.</p>
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
                                    <p>Implementação de nuvem Nextcloud para armazenamento de arquivos e implementação NVR Frigate com captura RTSP, máscaras de área e sistema de notificação.</p>
                                    <ul class="feature-icons">
                                        <li class="icon solid fa-cloud">Nextcloud, Docker</li>
                                        <li class="icon solid fa-video">Frigate, RTSP</li>
                                    </ul>
                                </div>
                            </article>
                            <article>
                                <div class="inner">
                                    <h4>Streaming de Áudio & Vídeo</h4>
                                    <p>Implementação de servidores Jellyfin (GPU Passthrough) para central de multimídia privada e Implementação de servidor icecast para audio marketing corporativo.</p>
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

        </div>              

        <section id="footer"> 
            <div class="container"> 
                <ul class="copyright"> 
                    <li>&copy; Rômulo Reuwsaat. All rights reserved.</li> 
                    <li><script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Fui útil? Pague um café!', '#72a4f2', 'S6S8PMDYA');kofiwidget2.draw();</script></li>                          
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

    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    <script type="text/javascript">
      (function() {
          // Substitua pelo seu Public Key do EmailJS
          emailjs.init("VlmQWkmDNbSyBtIbz");
      })();

      const btn = document.getElementById('button');

      document.getElementById('contact-form')
       .addEventListener('submit', function(event) {
         event.preventDefault();

         btn.value = 'Enviando...';

         const serviceID = 'service_p7twbbq';
         const templateID = 'template_syb7ork'; // Substitua pelo ID do seu template

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



