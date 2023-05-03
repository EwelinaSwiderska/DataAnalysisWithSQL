<h1>Data Analysis with SQL</h1>

- <b>[Google Colab link](https://colab.research.google.com/drive/1N8sbEmpTBpnRbxQ3PMT4KO7kGDaovMNw?usp=sharing)</b>


<h2>Description</h2>
<br>I have been given 3 CSV data files from Chat company to evaluate theirs users activity data(posts, comments) to find out more about users engagement in real world, which features they using the most and how this can help improve their applications in the future. </br>
<h3><b> Questions to answer: </b></h3>
<img width="883" alt="Screenshot 2023-05-03 at 09 06 36" src="https://user-images.githubusercontent.com/129959595/235862851-048cdc3c-3cf8-48f0-be4f-bf2bcf747a42.png">


<h2>Analysis walk-through:</h2>

<p align="left">
<br <h3> ⇨ Creating ER Diagram to find out relationships within ours data sets and name Primary  & Foreign keys <br/>
<br></br>
<img width="1011" alt="Screenshot 2023-04-29 at 18 16 37" src="https://user-images.githubusercontent.com/129959595/235316048-dd8347aa-1dde-4d80-b9c1-500ac11658e0.png">

<br></br>
<br />
<br />
⇨ Loading all data to our notebook and creating sqlite database. <br/>
<br></br>
<img width="1079" alt="Screenshot 2023-04-29 at 18 34 57" src="https://user-images.githubusercontent.com/129959595/235316303-64254923-9b91-4fbb-85d8-04a9111e4ef4.png">
<img width="1193" alt="Screenshot 2023-04-29 at 18 35 33" src="https://user-images.githubusercontent.com/129959595/235316311-77ee8053-7a4d-4daf-9ac5-ad728c17f1dc.png">


<br />
⇨ Checking all data for duplicates in each created table<br/>
<br></br>
<img width="1083" alt="Screenshot 2023-04-29 at 18 36 01" src="https://user-images.githubusercontent.com/129959595/235316404-b995269c-d558-477c-ad78-6bd4eae9de61.png">

<br><br/>

⇨ Evaluating our data sets to understand it more using simple checks(head()/ columns) <br/>
<br></br>
<img width="1313" alt="Screenshot 2023-04-29 at 18 44 02" src="https://user-images.githubusercontent.com/129959595/235316754-97bc0c4d-7055-4886-a068-315459782150.png">


<br />
<br />
⇨ Creating Tables with referential integrity and re-inserting data to our database <br/>
<br></br>
<img width="1173" alt="Screenshot 2023-04-29 at 18 49 10" src="https://user-images.githubusercontent.com/129959595/235317090-48655519-3aee-4ecd-a709-28d32cb385b2.png">
<img width="1060" alt="Screenshot 2023-04-29 at 18 49 31" src="https://user-images.githubusercontent.com/129959595/235317101-ed36b5ff-4f01-4518-9611-08801424373d.png">
<img width="1164" alt="Screenshot 2023-04-29 at 18 50 06" src="https://user-images.githubusercontent.com/129959595/235317117-0ef3cc8e-45f3-47ff-b81f-d2a0d7ccd17b.png">

<br />
<br />
⇨ Creating queries table to store our queries in case re-analysing our data in the future  <br/>
<br></br>
<img width="1324" alt="Screenshot 2023-04-29 at 18 51 00" src="https://user-images.githubusercontent.com/129959595/235317227-e522d3dd-3368-44d3-998c-76c862224cbe.png">
<img width="1102" alt="Screenshot 2023-04-29 at 18 58 30" src="https://user-images.githubusercontent.com/129959595/235317481-cea5efc5-a61c-49ee-b876-735f79c6442f.png">
<img width="1090" alt="Screenshot 2023-04-29 at 19 00 10" src="https://user-images.githubusercontent.com/129959595/235317624-b6c5f062-aaf3-484d-af7a-a2763dbd0822.png">

<br />
<br />
⇨ Performing some random data checks to make sure that everything is working correctly <br/>
<br></br>
<img width="1146" alt="Screenshot 2023-04-29 at 19 04 45" src="https://user-images.githubusercontent.com/129959595/235317918-4c1f256b-89f2-4b24-bb67-c0426111cfd6.png">
<img width="1275" alt="Screenshot 2023-04-29 at 19 12 08" src="https://user-images.githubusercontent.com/129959595/235317926-115d5adc-e0b0-4216-aff7-c0611253bf1f.png">
<img width="1207" alt="Screenshot 2023-04-29 at 19 20 49" src="https://user-images.githubusercontent.com/129959595/235318261-13e9b9af-a270-466d-8981-24a09bde9f25.png">

<br />
<br />
⇨ Writing queries to answer all questions from business requirements and checking if they are stored correctly in our queries table <br/>
<br></br>
<img width="1160" alt="Screenshot 2023-04-29 at 19 10 31" src="https://user-images.githubusercontent.com/129959595/235861705-425cd96a-244e-4b05-9ea5-b6cc546535cc.png">\
<br</br>
<img width="1127" alt="Screenshot 2023-05-03 at 08 54 46" src="https://user-images.githubusercontent.com/129959595/235861645-53a297a6-551f-44ca-991c-91cf333f79a2.png">
</b></h2>

<br />
<br />
<h2> To Consideration: </h2> <br/>
<br> ✔️ Some questions from business requirements are not clear(2 last questions from task 3)</br>
<br> ✔️ Personal informations could be easily found</br>
<br> ✔️ We should consider ethic point with our intended use of this data</br>

<br></br>
<h2>Additional knowlege:</h2>
<br> ✔️ Importance of Data Protection and GDPR</br>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
