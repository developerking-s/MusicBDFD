# Musica em Bdfd 

   - Video tutorial [click aqui](https://github.com/IzanaonYT/MusicScript/blob/main/Tutos/githubtuto.mp4)

Obten un Host Gratuita por ex a  [Railway.app](https://railway.app), para hospedar a api 

   - Video tutorial [click aqui](https://streamable.com/9qtqhr)
   
 Tutorial 2 "DISCORD_TOKEN" da valor do token de tu bot




```python
$onlyIf[$message!=;Escribe algo para escuchar]
$var[dominio; tu url de render aqui]
$var[json;{
    "guild_id": $guildID,
    "channel_id": $channelID,
    "user_id": $authorID,
    "url": "$url[encode;$message]"
}]
$httpPost[$var[dominio]/api/musica/;$var[json]]
$httpResult
```


- Codigos diferentes  o github dele : [Click aqui](https://github.com/IzanaonYT/MusicScript/blob/main/Tutos/codes_bdfd.md)
