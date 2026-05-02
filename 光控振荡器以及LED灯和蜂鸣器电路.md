#电路图：
![电路图][fig1]

[fig1]: https://i.postimg.cc/LnRtZTdx/ping-mu-jie-tu-2026-05-02-203933.png

注意：带有自激振荡器的电路都需要给直流接电容滤波，防止电源电压波动
核心电路：自激多谐音频振荡器

![振荡器原理图][fig2]

[fig2]: https://i.postimg.cc/3d7XDBMq/ping-mu-jie-tu-2026-05-02-203937.png

#光敏控制部分：

![光敏控制部分][fig3]

[fig3]: https://i.postimg.cc/Hjb0xNNB/ping-mu-jie-tu-2026-05-02-203945.png

#当环境光照较暗时，光敏电阻阻值大，V1基极电压低，V1截止，V2基极电压高，LED1熄灭，V2导通，R3被上拉至高电压，振荡器工作，LED2交替闪烁。
#当环境光照较亮时，光敏电阻阻值小，V1基极电压高，V1导通，V2基极电压低，LED1点亮，V2截止，R3悬空，音频振荡器停止工作。LED2熄灭。
