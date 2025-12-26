<!DOCTYPE html>
<html lang="ta">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Music Player</title>
</head>
<body style="font-family: Arial, sans-serif; text-align: center; background-color: #f2f2f2; padding: 20px; display: flex; justify-content: center; align-items: center; height: 90vh; margin: 0;">

  <div style="background-color: white; width: 280px; padding: 30px; border-radius: 20px; box-shadow: 0 10px 25px rgba(0,0,0,0.15);">
    
    <h2 style="color: #333; margin-bottom: 20px;">🎵 Music Player</h2>

    <div style="margin-bottom: 20px;">
      <img src="https://cdn-icons-png.flaticon.com/512/727/727245.png" 
           alt="Music Logo" 
           style="width: 80px; height: 80px; filter: drop-shadow(0 4px 5px rgba(0,0,0,0.1));">
    <div style="display: flex; justify-content: center; gap: 15px; margin-bottom: 25px;">
      <button style="width: 50px; height: 50px; border: none; background-color: #333; color: white; border-radius: 50%; cursor: pointer; font-size: 18px; transition: 0.3s;">⏮️</button>
      <button style="width: 60px; height: 60px; border: none; background-color: #ff4d4d; color: white; border-radius: 50%; cursor: pointer; font-size: 24px; transition: 0.3s;">▶️</button>
      <button style="width: 50px; height: 50px; border: none; background-color: #333; color: white; border-radius: 50%; cursor: pointer; font-size: 18px; transition: 0.3s;">⏭️</button>
    </div>

    <div style="background-color: #eee; height: 6px; width: 100%; border-radius: 10px; position: relative; overflow: hidden;">
      <div style="background-color: #ff4d4d; width: 45%; height: 100%; border-radius: 10px;"></div>
    </div>
    
    <div style="display: flex; justify-content: space-between; margin-top: 8px; font-size: 12px; color: #999;">
      <span>1:45</span>
      <span>3:50</span>
    </div>

  </div>

</body>
</html>
