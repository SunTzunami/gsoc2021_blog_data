<h2> First week of coding </h2>
<p>Welcome to the second weekly check-in. I'll be sharing my progress for the first week of coding.</p>
<h2> What did you do this week? </h2>
<p> I implemented the space filling model for proteins and created a PR for the same.
<br>
  Preview (protein rendered: <a href="https://www.rcsb.org/structure/3pgk">3pgk</a>) -
<br>
<img alt="https://user-images.githubusercontent.com/65067354/121518963-b92cb580-ca0e-11eb-8232-3512edc04670.png"
     src="https://user-images.githubusercontent.com/65067354/121518963-b92cb580-ca0e-11eb-8232-3512edc04670.png">
<br>
The PR has: 
<ul><li>Actor for space_filling_model</li>
<li>Two examples where I show how to visualize the proteins- 
 <ol><li>In <a href="https://github.com/fury-gl/fury/pull/439/files#diff-9579793ad0f25aa895d88d92a09b49f616969d3b1c859be14a16c469572dc92bR6">this example</a>, 
I parse a PDBx file myself and extract the atomic info essential for constructing the model which is then used by the actor to visualize it.</li>
<li> In <a href="https://github.com/fury-gl/fury/pull/439/files#diff-1a09073039495e53b9585d0fd64c58247e98c5659d3cc84be8abe6b2724c3718R6">this example</a>, 
I parse a PDB file by using Biopython module and extract the atomic info essential for constructing the model which is then used by the actor to visualize it.</li>
</ol>
<li>I created a basic test for the actor which needs to be improved. I'll discuss how to improve the test with the mentors.
</ul>
</p>
<h2>What is coming up next week?</h2>
<p> I'll try to implement ball and stick model or ribbon model depending on which model is decided in the meeting with the mentors and try to improve the tests for space filling model. Writing an algorithm to generate bonds from structure data will be the challenge</p>
<h2>Did you get stuck anywhere?</h2>
<p> I tried to create a class in python which inherits from a vtkclass called vtkMoleculeReaderBase but was unsucessful in this endeavour. I'll try to find a workaround.</p>
