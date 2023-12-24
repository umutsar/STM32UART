# STM32UART

# STM32F103C8T6 Kartı için yazıldı. 

While içerisinde delay kullanmamın sebebi veri güvenliğindendir. anlık elektrik kesintisinde initial değerler bellekte herhangi bir yerden alabiliyor. Bu durumdan kurtulmak için beklemeye aldım ve sorunu çözdüm. Tüm kodlarda iç içe while koyup parent while'ın hemen altına delay koymayı unutmayınız. 
