u=document.getElementById('findipurl'); 
h='Free users please don\'t remove our link. Get <a href=\'https://www.find-ip.net/ip-script\' target=\'_blank\'>the code</a> again.'; 
if(u&&(a=u.querySelector('a'))&&(r=a.href)&&-1!=r.indexOf('find-ip.net')){
  h='<style>
    #findipinfo {
      background-color: #2b2b2b;
      color: #00ff00;
      padding: 10px;
      border: 1px solid #00ff00;
      box-shadow: 0px 0px 10px #00ff00;
      animation: kelap-kelip 1s infinite;
    }
    @keyframes kelap-kelip {
      0% {
        box-shadow: 0px 0px 10px #00ff00;
      }
      50% {
        box-shadow: 0px 0px 20px #00ff00;
      }
      100% {
        box-shadow: 0px 0px 10px #00ff00;
      }
    }
  </style>
  <a id="findipinfo" href="http://www.find-ip.net/" target="_blank">
    <div>IP Anda : <b></b></div>
    <div> Negara : <b></b> <img src="//api.find-ip.net/flags/.png" alt="()" width="16" height="11" /></div>
    <div> Wilayah : <b></b></div>
    <div> Kota : <b></b></div>
    <div> Bahasa : <b></b></div>
    <div> Browser : <b></b></div>
    <div> Sistem : <b></b></div>
  </a>';
} 
if(!u){u=document.currentScript;} 
w=document.getElementById('findipwidget'); 
if(!w){w=document.createElement('div');u.parentNode.insertBefore(w, u);} 
w.innerHTML=h;
