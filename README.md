# meetapp
meetapp is free adobe connect alternatives for visual classrooms , online meetings, screen share,   webinars , video and audio conferencing.
<div>
 <img src="/img/Capture-2.png" style="width:100%" /> 
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
    <li>Permissions management </li>
     <li>Collaboration online IDE (html javascript and css) </li>
     <li>record (webm mp4 mkv format) </li>
     <li>live (hls) </li>
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
  
  <pre>
  
   install docker and docker-compose in your os (for windows install docker desktop)  
   $ git clone https://github.com/sunmobiir/meetapp.git
   $ cd meetapp
   open .env file and replace example.com with a domain or subdomain and inter valid ip (.env file is hidden)
   $ docker-compose up -d  
  
  </pre>
  <p>By executing the above command, Docker will run and download and install the software, as well as provide the required ssl use letsencrypt</p>
  <p>wait 4 minutes to activate all services</p>
  <p>The software is installed open the chrome browser and enter the https://yourdomain.com</p>
  <p>admin login ==== user : 'admin' and  pass : 'public' </p>   
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
  <br /><a  target="_blank" href='https://microsoft.github.io/monaco-editor/'> Monaco Editor </a> 
 
  
<h3>&nbsp;</h3>

<h3>comparison of meetapp(learn100) and adobe connect and&nbsp;bigbluebutton</h3>

<p>&nbsp;</p>

<table border="2" cellpadding="3" cellspacing="1" style="width: 665px;">
	<thead>
		<tr>
			<th scope="row" style="width: 251px;">&nbsp;</th>
			<th scope="col" style="width: 125px;">adobe connect</th>
			<th scope="col" style="width: 158px;">bigbluebutton</th>
			<th scope="col" style="width: 90px;">meetApp</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row" style="width: 251px;"><strong>whiteboard</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>Office suite</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>desktop sharing</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>Video&nbsp;conferencing</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>file sharing</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>collaboration diagram</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>collaboration math editor</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>collaboration online IDE</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>record</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>record (webm , mp4,mkv)</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;">
			<p><strong>+</strong></p>
			</td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>live (hls)</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>stream to&nbsp;youtube ,&nbsp;instagram&nbsp;</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>breakout rooms</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>-</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p><strong>play video file</strong></p>
			</th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>free&nbsp;</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>linux install</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>windows install</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>+</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;"><strong>open source</strong></th>
			<td class="text-align-center" style="width: 125px;"><strong>-</strong></td>
			<td class="text-align-center" style="width: 158px;"><strong>+</strong></td>
			<td class="text-align-center" style="width: 90px;"><strong>-</strong></td>
		</tr>
		<tr>
			<th scope="row" style="width: 251px;">
			<p>&nbsp;</p>
			</th>
			<td class="text-align-center" style="width: 125px;"><b>&nbsp;</b></td>
			<td class="text-align-center" style="width: 158px;"><b>&nbsp;</b></td>
			<td class="text-align-center" style="width: 90px;"><b>&nbsp;</b></td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p>








 



