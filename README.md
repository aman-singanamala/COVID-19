<p align="center">The global pandemic of COVID-19 has an impact on health care and lifestyle around the world, and early detection is crucial for limiting case spread and mortality. The Reverse transcription Polymerase chain reaction (RT-PCR) is the most widely used diagnosis test; nevertheless, the time and expense of these tests are prohibitive, necessitating the use of additional quick and accessible diagnostic methods. This paper's technique is based on recent research that links the presence of COVID-19 to results in chest X-ray pictures. It processes these images and classifies them as positive or negative for COVID-19 using existing deep learning models (VGG19 and U-Net). The suggested system includes a preprocessing stage with lung segmentation, which removes the surrounds that do not provide significant information for the task and may cause biased findings; after this first stage, the proposed system moves on to the next stage, which is the analysis</p>
<hr>

</br>
<p align="center"> <img src="https://user-images.githubusercontent.com/84006448/168418645-2462461e-4306-4dda-b56f-f3f7c59b94b6.png" alt="Aman Singanamala" /> </p>
<hr>
</br>
<p align="center"> <b> PROCEDURE </b> </p>

<a href ="https://www.kaggle.com/datasets/francismon/curated-covid19-chest-xray-dataset"> <p align="center"> <img src="https://user-images.githubusercontent.com/84006448/168418683-5763f29a-1d87-4ec5-9ff0-a0abd228521c.png" alt="Aman Singanamala" /> </p> </a>

<hr>


<h1 align="center" style="font-size:20vw">Data-Set Used</h1>
<a href="https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database" target="_blank"><p align="center"> <img src="https://user-images.githubusercontent.com/84006448/168419291-4745e998-a4ae-49e3-8e18-68e1955f8c8c.png" alt="Aman Singanamala" /> </p></a>

<hr>

 
<h2 style="font-size:20vw"> Tech Stack </h2>

<ul>
  <li> Python ( for ML and Streamlit) </li>
</ul>



<h2 style="font-size:20vw"> Key-Words </h2>

<ul>
  <li> Keras </li>
  <li> Tensor-Flow </li>
  <li> OpenCV </li>
  <li> scikit-learn</li>
  <li> Streamlit </li>
  <li> CNN (Convolution Neural Network ) </li>
</ul>


</br>

<p  align="center"> Creating a Model is not sufficient, we also need to ensure the model in real life by 
everyone. We thought of creating a web application where we can upload the Xray 
as input. The output will be decided the by the model whether it has Covid or NoCovid. 
We used Streamlit, which is a Python Frontend Framework for deploying Machine 
Learning, Deep Learning Models on Web Application. </p>
















![image](https://user-images.githubusercontent.com/84006448/164777993-4010abf4-1c84-464d-a6c6-cb4ca8d7f9b3.png)

