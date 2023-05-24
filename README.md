

Simple face detector for simpsons. Used on seasons 25-28 it created a database of 9,878 images. 

Each image:
<ul>
  <li>is focused on a single face</li>
  <li>has size 200x200</li>
  <li>is paired with a simplified version of itself, which only presents the skin and eyes of the detected face.</li>
</ul>
<div align='center' min-width=820>
  <img src='img.png' width=400 float='left'>
  <img src='faces.png' width=400 float='right' >
</div>


<code>get_faces.ipynb</code> gets the link of a directory where the video files are stored and extracts 150 images from each episode. Subsequently, it calls <code>find_face()</code> from <code>face_detector.py</code> which applies a variety of filters on each image in order to detect a face.


