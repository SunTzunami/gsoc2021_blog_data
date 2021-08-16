<h2>Tenth week of coding </h2>
<p>Welcome to the tenth weekly check-in. I'll be sharing my progress for the ninth week of coding.</p>
<h2> What did you do this week? </h2>
<p><ol>
  <li>Implemented <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0008140">this<a> paper to generate <b>Van Der Waals surface</b> and <b>solvent-accessible surface</b>. It was a good learning experience because the first time I read the paper, I didn't understand the underlying math, it all seemed alien to me. I had to read it many times, read up the algorithms used and understand the terminologies. I had a meeting with mentorrs to understand a bit of the theory which proved to be quite fruitful as I understood how to go about making the space-filling model. <a href="https://pyscience.wordpress.com/2014/09/11/surface-extraction-creating-a-mesh-from-pixel-data-using-python-and-vtk/">This</a> blog was kinda helpful in understanding how to use vtkMarchingCubes with numpy arrays.</li>
    <li>One of the earliest SAS rendering looked like this (this implementation was not strictly according to the paper):
      <br><img src="https://user-images.githubusercontent.com/65067354/129559593-baf201bf-720c-45f7-9269-3b31954efd5e.png" width="300" height="300">
<br>
  Current render (this implementation was according to the paper): <br>
   <figure><img src="https://user-images.githubusercontent.com/65067354/129560374-14180b22-14b2-449b-88a6-b3140226418d.png" width="300" height="300">
    <figcaption>grid dimenstions = 256×256×256</figcaption>
</figure>
  </li></ul></li>
  <li>I also understood how to go about rendering volume. I think ability to render volumes with FURY will be a cool capability and I'll discuss my implementation and ask them for feedback.
    Example of volume rendering: 
    <br>
    <img src="https://user-images.githubusercontent.com/65067354/129562606-50a9f0cf-e16d-4501-b0fa-a0038fda406b.png" width="300" height="300">
  </li></ol>
</p>
<h2>What is coming up next week?</h2>
<p>
  I'll try to get <a href="https://github.com/fury-gl/fury/pull/452">PR #452</a> merged, add a tutorial for the molecular module and create a PR for molecular surface representations.
</p>
<h2>Did you get stuck anywhere?</h2>
<p>The paper I was trying to implement seemed quite intimidating at first. Understanding it and the underlying math took a few days. Implementing it in python was also a challenge as usage of vtkMarchingCubes is not that well documented for numpy arrays. All in all, it was a nice learning experience.</p>
