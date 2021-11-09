# Проектная работа 
Яндекс практикум

В этом проекте используется базовый набор элементов вёрстки для новичка! Также сайт был написан и оформлен по _БЭМ_ методологии.

##### Здесь используются:

* *Кейфрам*

```
 @keyframes rotation {
   0% {
      transform: rotate(0deg);
   }

   100% {
      transform: rotate(360deg);
   }
}

a {
   transition: opacity 0.2s linear;
}
a:hover {
   opacity: 0.7;
} 
```

* *Трансформация*

```
.kaufman__triangle {
   background-image: url(/images/kaufman-triangle.svg);
   background-size: contain;
   width: 877px;
   height: 877px;
   position: absolute;
   right: -210px;
   top: 0;
   z-index: 0;
   transform: rotate(360deg);
   animation: rotation linear 20s infinite;
}

```
* *Iframe*
```
<iframe src="https://www.youtube.com/embed/arj7oStGLkU" title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen class="video__iframe"></iframe>

```

И другие прочее...