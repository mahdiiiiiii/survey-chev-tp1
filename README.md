<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Merci !</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: -apple-system, Segoe UI, Roboto, sans-serif;
      text-align: center;
      background-color: #f5f5f5;
      color: #444;
      padding-top: 120px;
    }
    h1 {
      font-size: 22px;
      font-weight: 500;
      color: #333;
    }
  </style>
</head>
<body>

  <h1>Merci d'avoir répondu à notre sondage !</h1>

  <script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');

  fbq('init', '000000000000000');
  fbq('trackCustom', 'SondageComplete');
  </script>
  <noscript><img height="1" width="1" style="display:none"
  src="https://www.facebook.com/tr?id=000000000000000&ev=SondageComplete&noscript=1"
  /></noscript>

</body>
</html>
