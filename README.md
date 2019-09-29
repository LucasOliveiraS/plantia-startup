# PlantIA

![alt text](https://github.com/LucasOliveiraS/plantia-startup/blob/master/img/logo.png)

Projeto focado na classificação de imagens de plantas que podem estar com sintomas de doenças. O usuário irá acessar a aplicação web e colocar a foto de uma planta que ele deseja analisar algum tipo de anomalia.


As doenças encontradas em plantas podem afetar todas as espécies. A maioria das doenças são diagnosticadas pelos sintomas que elas exibem na planta.

Como ocorre com todas as doenças, é importante identificar rapidamente e tratar para evitar surtos de crescimento ou morte potencial das plantas. Em grande parte dos casos, o tratamento no início da anomalia pode resolver a maioria das doenças botânicas.

![alt text](https://github.com/LucasOliveiraS/plantia-startup/blob/master/img/plantas-exemplo.jpeg)

Realize o download do modelo de Deep Learning em Keras, acessando o <b>output</b> desse 
<a href="https://www.kaggle.com/oliveirasp6/plant-disease-detection-using-keras/output?scriptVersionId=21258537">Notebook.</a> 


Para construir o container Docker, execute:

<code>sudo docker build -t keras-app:latest .</code>

Para rodar o container, execute:

<code>sudo docker run -d -p 5000:5000 keras-app</code>

Você pode testar o modelo utilizando o seguinte código:

<code>curl -X POST -F image=@plant.jpg 'http://localhost:5000/predict'</code>

<h3>Projeto</h3>

Para saber mais sobre o projeto, você pode ler esse  <a href="https://medium.com/@lucasoliveiras/plantia-startup-para-classifica%C3%A7%C3%A3o-de-plantas-com-doen%C3%A7as-258d75928f30"><b>artigo</b></a> que explica alguns conceitos fundamentais da aplicação.

<h3>Autor</h3>
<h4>Lucas Oliveira</h4>

 <ul>
  <li><a href="https://github.com/LucasOliveiraS">Github Profile</a></li>
  <li><a href="https://www.linkedin.com/in/lucas-oliveira-492723127/">Linkedin</a></li>
  <li><a href="https://medium.com/@lucasoliveiras">Medium</a></li>
</ul>
