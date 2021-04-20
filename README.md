# meetapp
meetapp is free adobe connect alternatives for visual classrooms , online meetings, screen share,   webinars , video and audio conferencing.
<div>
 <img src="/img/Capture.png" style="width:100%" /> 
</div>
<h2 align="center">Features</h2>
<p><p> 
  <ul>
<li>Advanced interactive whiteboard </li>
<li>Collaboration online Office suite  </li>
    <li>Team collaboration</li>
<li> Chat </li>
<li>Desktop sharing</li>
    <li>Video and audio conferencing</li>
     <li>File sharing</li>
     <li>Polls</li>
     <li>Play video file</li>
     <li>Collaboration diagram</li>
     <li>Collaboration math editor</li>
    <li>Member roles</li>
</ul>
<h4>online demo </h4>
<a href='https://en.learn100.ir/'>demo</a>
<h4>os support</h4>
<ul>
  <li>Linux server</li>
  <li>Windows server</li>
  <li>FreeBSD </li>
  </ul>
<h4><strong>Requirements</strong></h4>
<ul>
  <li>ip</li>
  <li>domain or subdomain</li>
   <li>docker</li>
  </ul>
 
 
<h2 align="center">install meetapp</h2>
 
  <p style="text-align: left;">The installation process is very easy and can be installed in less than 5 minutes</p>
  <p>Temporarily disable firewall</p>
  <p>if use windows server , disable iis to release 80 and 443 ports</p>
  <ul>
  <li> install docker in your os </li>
    <li> clone this repository</li>
    <li> cd meetapp</li>
  <li> open .env file and replace example.com with a domain or subdomain</li>
  <li>docker-compose up -d </li>
  </ul>
  <p>By executing the above command, Docker will run and download and install the software, as well as provide the required ssl use letsencrypt</p>
  <p>The software is installed Open the Chrome browser and enter the https://yourdomain.com</p>
  <p></p>   
  <br /> <br /> <p>To develop this software, free and open source packages have been used, which include the following : </p>
    
   
 
 
  <br /><a  target='_blank' href='https://github.com/webrtc'>webrtc</a> for audio and video conference
  <br /><a  target="_blank" href='https://github.com/open-webrtc-toolkit/owt-server'>intel&reg; collaboration suite</a> for webrtc
  <br /><a  target="_blank" href='https://github.com/google/boringssl'>BoringSSL</a>     (fork of OpenSSL) by google for ssl validation
  <br /><a  target="_blank" href='https://letsencrypt.org/'>letsencrypt</a>
  <br /><a  target="_blank" href='https://github.com/dotnet/aspnetcore'>asp.net core</a>
  <br /><a  target="_blank" href='https://getbootstrap.com/'>bootstrap</a> for front end design
  <br /><a  target="_blank" href='https://github.com/coturn/coturn'>coturn</a> server for nat traversal
  <br /><a  target="_blank" href='https://openresty.org/en/'>OpenResty</a> (nginx base webserver) for reverse proxy
  <br /><a  target="_blank" href='https://www.ffmpeg.org/'>ffmpeg</a> 
  <br /><a  target="_blank" href='https://libwebsockets.org/'>libwebsocket</a> for websocket communication
  <br /><a  target="_blank" href='https://www.docker.com/'>docker</a> for container management 
  <br /><a  target="_blank" href='http://visualmatheditor.equatheque.net/index.html'>Visual Math Editor</a> 
  <br /><a  target="_blank" href='https://github.com/jgraph/drawio'>online diagramming web</a> 
  <br /><a  target="_blank" href='https://github.com/traefik/traefik'>HTTP reverse proxy </a> 
  <br /><a  target="_blank" href='https://github.com/CollaboraOnline/online'> collaborative online office suite </a> 
 
  








 



