<!DOCTYPE html>
<html>
<head>
  <title>Teste de Câmera</title>
</head>
<body>
  <h1>Clique para testar sua câmera</h1>
  <video id="video" width="640" height="480" autoplay></video>
  <script>
    navigator.mediaDevices.getUserMedia({video: true})
      .then(stream => {
        document.getElementById('video').srcObject = stream;
      })
      .catch(() => alert('Permissão negada'));
  </script>
</body>
</html>
