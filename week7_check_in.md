<h2>Sixth week of coding </h2>
<p>Welcome to the sixth weekly check-in. I'll be sharing my progress for the sixth week of coding.</p>
<h2> What did you do this week? </h2>
<p>
<ol>
  <li>Updated <a href="https://github.com/fury-gl/fury/pull/452">Molecular module</a>: made it more pythonic, implemented ribbon actor, 
    added support to pass numpy arrays (earlier, atomic data could only be added by using the add_atom)</li>
  <li>Created a <a href="https://github.com/fury-gl/fury/pull/462">PR</a> to - <ul>
    <li>update the helical motion animation to use a single line actor, 
    added textblocks to display velocity of the particle. Preview - 
    <br> 
    <img src="https://user-images.githubusercontent.com/65067354/126033284-882ed6fd-fcc3-4a1c-8dfd-3220908859b1.png" width="400" height="300">
      <br>
    </li>
    <li>For brownian motion animation, I removed rotation(azimuth) and box actor, added textblock to 
    display the number of particles and to show the simulation steps. Preview - 
    <br>
    <img src="https://user-images.githubusercontent.com/65067354/126033291-da68cb0d-b856-48ad-9aa4-c46621052267.png" width="400" height="400">
    <br>
    </li>
</ul></li>
<li>Updated surface animation (used gridUI, added multiple animations). Preview -
<br>
<img src="https://user-images.githubusercontent.com/65067354/126061012-b183a47d-ed5e-4026-938b-4124da291524.png" width="400" height="400">
<br>
</li>
<li>Created a <a href="https://discourse.vtk.org/t/vtkmoleculemapper-gaps-in-bonds-on-zooming-in/6183">topic</a> on vtk discourse forum to query about 
      gaps in bonds (tried resolving it by manipulating vtkProperties: BackfaceCulling, FrontfaceCulling but was unsuccessful)</li>
<li>Read about molecular surface (theory behind it)</li></ol>
</p>
<h2>What is coming up next week?</h2>
<p><ol>
  <li>Update molecular module by adding tests, ribbon actor.</li>
  <li>Try to implement molecular surface representation</li>
  <li>Interactivity of the molecules</li>
  </ol>
  </p>
<h2>Did you get stuck anywhere?</h2>
<p>I didn't get stuck anywhere this week.</p>
