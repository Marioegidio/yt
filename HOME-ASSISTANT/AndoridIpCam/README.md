
camera:
  - platform: mjpeg
    name: my cam
    mjpeg_url: http://YOUR_IP:YOUR_PORT/video
    still_image_url: http://YOUR_IP:YOUR_PORT/picture/1/current/
    username: YOUR_USERNAME
    password: YOUR_PASSWORD

android_ip_webcam:
  - host: YOUR_IP
    port: YOUR_PORT
    username: YOUR_USERNAME
    password: YOUR_PASSWORD
    sensors:
      - audio_connections
      - battery_level
      - battery_temp
      - battery_voltage
      - light
      - motion
      - pressure
      - proximity
      - sound
      - video_connections
    switches:
      - exposure_lock
      - ffc
      - focus
      - gps_active
      - motion_detect
      - night_vision
      - overlay
      - torch
      - whitebalance_lock
      - video_recording
