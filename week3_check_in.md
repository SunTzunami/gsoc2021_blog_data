<h2>Second week of coding </h2>
<p>Welcome to the second weekly check-in. I'll be sharing my progress for the second week of coding.</p>
<h2> What did you do this week? </h2>
<p> I created an example to demonstrate how one can render multiple bonds (double and triple). This required me to write an algorithm to detect bonding. I used <a href="https://www.kaggle.com/aekoch95/bonds-from-structure-data">this</a> as a reference and made a few tweaks of my own to detect the presence of double/triple bonds from interatomic distances. The math involved in generating the coordinates of bonds was quite intriguing.
<br> 
  Preview (molecules rendered: Ethane, Ethene, Ethyne from left to right) - 
<br>
<img height="300" src="https://user-images.githubusercontent.com/65067354/122672109-7d040c80-d1e7-11eb-815d-1d07fe47bbc4.png" width="300">
<br>
</p>
<p>
 In addition to this, I tried understanding the codebase of vtkMolecule, vtkSimpleBondPerceiver, vtkMoleculeMapper, vtkPeriodicTable and was able to render bond-stick models and stick models using it.
This will be of great help although it's rather slow in rendering large molecules (using shaders to improve its speed will be crucial if it's to be utilised).
</p><ul>
<li>Preview of Stick representation using vtkMolecule - 
<br>
<img height="300" src="https://github.com/SunTzunami/gsoc2021_blog_data/blob/master/visuals/week2_wire_rep.png?raw=true" width="300">
</li>
<li>Preview of Ball and Stick representation using vtkMolecule - 
<br>
<img height="300" src="https://github.com/SunTzunami/gsoc2021_blog_data/blob/master/visuals/week2_bs_rep.png?raw=true" width="300">
<br>
</li>
</ul>
<p></p>
<h2>What is coming up next week?</h2>
<p>Try to implement the above models using shaders. Try implementing the ribbon model using the vtkProteinRibbonFilter. The rest will be decided in the meeting with the mentors.</p>
<h2>Did you get stuck anywhere?</h2>
<p> Predicting bonds had been a problem since the past few weeks, it was resolved to a large extent by vtkSimpleBondPerceiver (the only limitation of vtkSimpleBondPerceiver being its inability to predict multiple bonds).
</p>
