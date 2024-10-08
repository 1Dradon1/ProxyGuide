ВНИМАНИЕ, ЕСЛИ ВАС ПРОСЯТ ПРАВА АДМИНА, ПРОСТО ПРЕДОСТАВЬТЕ ИХ НА ВСЕ ЗАПРОСЫ СОГДАШАЕМСЯ, НАЖИМАЕМ ДА\YES 

заходим [сюда](https://github.com/Matsuridayo/nekoray/releases)
листаем чуть-чуть вниз
качаем nekoray-4.0-beta3-2024-07-13-windows64.zip(версия может меняться)
![Pasted image 20241008223129](https://github.com/user-attachments/assets/d22c9419-0493-4c74-836d-88f03bdd6282)

папку с прогой кладем куда удобно, затем запускаем nekobox.exe

копируем из ConnectionInfo тот впн сервер который нам больше нравится

например этот

![Pasted image 20241008223400](https://github.com/user-attachments/assets/a66e655d-ab1d-4c79-8d68-3d37595dad70)

теперь кликаем по порядку как на скринах

![Pasted image 20241008223624](https://github.com/user-attachments/assets/b49e0a8e-ea67-4feb-b6ae-38cbd5f950d6)


![Pasted image 20241008223745](https://github.com/user-attachments/assets/c76f9fd2-d596-4de7-8f7e-e06f7231d065)



![Pasted image 20241008223842](https://github.com/user-attachments/assets/e7d89a3d-f798-41f1-8713-56ad70cec429)

![Pasted image 20241008224038](https://github.com/user-attachments/assets/8b599078-6423-4660-9868-976fae5c7c37)

в то же поле, что и у меня добавляем все это и включаем bybass

```
domain:youtube.com
domain:www.youtube.com
domain:m.youtube.com
domain:youtube.googleapis.com
domain:youtubei.googleapis.com
domain:ytimg.com
domain:ytstatic.l.google.com
domain:s.ytimg.com
domain:i.ytimg.com
domain:googlevideo.com
domain:ytimg.l.google.com
domain:yt3.ggpht.com
domain:yt3.googleusercontent.com
domain:googleapis.com
domain:gstatic.com
domain:googleusercontent.com
domain:ggpht.com
domain:ytimg.l.googleusercontent.com
domain:clients1.google.com
domain:clients2.google.com
domain:clients3.google.com
domain:clients4.google.com
domain:clients5.google.com
domain:clients6.google.com
domain:discord.com
domain:cdn.discordapp.com
domain:discord.gg
domain:discordapp.com
domain:gateway.discord.gg
domain:media.discordapp.net
domain:status.discord.com

```

![Pasted image 20241008224244](https://github.com/user-attachments/assets/4961ea35-bceb-451b-bf14-1a964be4cf24)


нажимаем на ок

выделяем добавленный профиль нажатием по нему и нажимаем Enter

![Pasted image 20241008225948](https://github.com/user-attachments/assets/fc285fe4-7c37-4439-b3ab-48daaacdc128)


После этих действий у нас работает впн в режиме белого списка и пропускает только трафик только тех доменов(сайтов) которые мы указали в предыдущем действии

Теперь любимое: фикс дискорда

![Pasted image 20241008230353](https://github.com/user-attachments/assets/2d026243-a4fc-4d6d-9204-c2f722bcef33)


![Pasted image 20241008230337](https://github.com/user-attachments/assets/018f2b72-0cd3-4baf-b1b2-f5bda5164790)


Внимание, на данный момент полноценного решения нет, поэтому придется идти на ухищрения и прокликивать настройки для того что бы **подключиться на канал или подключиться\дать стрим в дискорде

ставим эту галочку
![Pasted image 20241008230717](https://github.com/user-attachments/assets/6abba42a-bcdb-4bcc-8dbf-6558b226ce5c)

и меняем bypass на proxy

![Pasted image 20241008230817](https://github.com/user-attachments/assets/38760fae-6404-4ef9-a273-0bf2bd7e5e65)

после этих действий можно подключаться к дискорду 

затем можно и даже нужно переключить proxy обратно на bypass(некоторых отключает если его переключить, тогда оставьте proxy) и выключить режим tun(его выключаем всегда), что бы весь трафик не фильтровался 
