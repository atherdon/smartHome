ngrok -config ngrok.cfg -subdomain 481b4659.ngrok.com 3000


//步进电机顺时针转（开窗）
26 53 52 53 00 00 00 00 00 00 00 00 00 00 42 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A
//步进电机逆时针转（关窗）
26 53 52 53 00 00 00 00 00 00 00 00 00 00 42 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A


//开继电器1（开灯）
26 53 52 53 00 00 00 00 00 00 00 00 00 00 4A 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A
//关继电器1（关灯）
26 53 52 53 00 00 00 00 00 00 00 00 00 00 4A 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A


//开继电器2
26 53 52 53 00 00 00 00 00 00 00 00 00 00 4A 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A
//关继电器2
26 53 52 53 00 00 00 00 00 00 00 00 00 00 4A 01 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A


//回家模式（开继电器1,2 步进顺）
26 53 52 53 00 00 00 00 00 00 00 00 00 00 5A 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A、
//离家模式(关继电器1,2，步进逆)
26 53 52 53 00 00 00 00 00 00 00 00 00 00 5A 01 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 2A
