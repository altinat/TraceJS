<h3 style="text-align: left;">This bot can help you to find any anime by screenshot.</h3>
<h1 style="text-align: center;">INSTRUCTION:</h1>
[<img src="https://open.autocode.com/static/images/open.svg?" width="192">](https://open.autocode.com/)
<p>
<h3>Installation: <br></h3>
1) Create mysql table:  <br>
CREATE TABLE `guilds` (<br>
  `guild_id` varchar(21) CHARACTER SET utf8 COLLATE utf8_unicode_ci NOT NULL,<br>
  `workchannel` varchar(18) CHARACTER SET utf8 COLLATE utf8_unicode_ci NOT NULL,<br>
  `lang` varchar(10) COLLATE utf8_unicode_ci NOT NULL DEFAULT 'eng'<br>
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;
)<br>
2) Install node.js,<br>
3) Edit config.js <b><br>( if you don't have trace.moe token set "trace_moe_token": false )</b>,<br>
4) Start bot: cmd -> <b>node index.js</b><br>
5) Add bot to your server,<br>
6) Set work channel: <b>+setchannel #channel_name</b><br>
7) Send any anime image to work channel ;D<br>
</p>
