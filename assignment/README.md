# Beberapa perubahan
1. Ketika pertama kali di apply, ada beberapa error yang terbaca seperti *matchLabels* yang tidak sesuai, *request* dan *resource* limit yang tidak sesuai. ketika diganti agar *request* < *resource*,  apply bisa dilakukan
2. Ada Bug pull error dari pods, ternyata nginx 1.27.1 itu tidak ada, ketika diganti ke tag latest, bisa dijalankan
3. Bug **crashloopbackoff** pada seluruh pods, ini saya masih bingung kenapa, tapi ketika readinessProbe dan livenessProbe di comment, pods bisa berjalan dengan baik