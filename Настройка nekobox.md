заходим [сюда](https://github.com/Matsuridayo/nekoray/releases)
листаем чуть-чуть вниз
качаем nekoray-4.0-beta3-2024-07-13-windows64.zip(версия может меняться)
![[Pasted image 20241008223129.png]]
папку с прогой кладем куда удобно, затем запускаем nekobox.exe

копируем из ConnectionInfo тот впн сервер который нам больше нравится

например этот
![[Pasted image 20241008223400.png]]

теперь кликаем по порядку как на скринах

![[Pasted image 20241008223624.png]]

![[Pasted image 20241008223745.png]]

![[Pasted image 20241008223842.png]]![[Pasted image 20241008224038.png]]
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

![[Pasted image 20241008224244.png]]

нажимаем на ок

выделяем добавленный профиль нажатием по нему и нажимаем Enter
![[Pasted image 20241008225948.png]]


**После этих действий у нас работает впн в режиме белого списка и пропускает только трафик только тех доменов(сайтов) которые мы указали в предыдущем действии

**Теперь любимое: фикс дискорда

![[Pasted image 20241008230353.png]]

![[Pasted image 20241008230337.png]]

Внимание, на данный момент полноценного решения нет, поэтому придется идти на ухищрения и прокликивать настройки для того что бы **подключиться на канал или подключиться\дать стрим в дискорде

ставим эту галочку
![[Pasted image 20241008230717.png]]
и меняем bypass на proxy
![[Pasted image 20241008230817.png]]
после этих действий можно подключаться к дискорду 

затем можно и даже нужно переключить proxy обратно на bypass(некоторых отключает если его переключить, тогда оставьте proxy) и выключить режим tun(его выключаем всегда), что бы весь трафик не фильтровался 