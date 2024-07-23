<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLS Selfie</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        h1 {
            margin-bottom: 20px;
        }
        video, canvas {
            display: none;
        }
        #video {
            display: block;
            width: 320px;
            height: 240px;
            background-color: #333;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>BLS Selfie</h1>
    <video id="video" autoplay></video>
    <canvas id="canvas"></canvas>
    <button id="startSelfie">Démarrer le Selfie</button>
    <script>
        const video = document.getElementById('video');
        const canvas = document.getElementById('canvas');
        const button = document.getElementById('startSelfie');

        button.addEventListener('click', async () => {
            try {
                const stream = await navigator.mediaDevices.getUserMedia({ video: true });
                video.srcObject = stream;
                video.style.display = 'block';
                canvas.style.display = 'none';
            } catch (error) {
                console.error('Erreur d\'accès à la webcam:', error);
            }
        });

        video.addEventListener('click', () => {
            canvas.width = video.videoWidth;
            canvas.height = video.videoHeight;
            canvas.getContext('2d').drawImage(video, 0, 0, canvas.width, canvas.height);
            video.style.display = 'none';
            canvas.style.display = 'block';
        });
    </script>
</body>
</html>
