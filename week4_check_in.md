<h2>Third week of coding </h2>
<p>Welcome to the third weekly check-in. I'll be sharing my progress for the third week of coding.</p>
<h2> What did you do this week? </h2>
<p> I made a document with code snippets and visuals to show how one can use some vtk classes in python for molecular visualization.
Classes of interest - 
<ul>
  <li>vtkMolecule (store atomic information about the molecule)</li>
  <li>vtkSimpleBondPerceiver (calculate bonding info for a vtkMolecule)</li>
  <li>vtkMoleculeMapper (mapper to draw vtkMolecule object)</li>
  <li>vtkPeriodicTable (stores chemical data sourced from the Blue Obelisk Data).</li>
</ul>
Link to the document - <a href="https://docs.google.com/document/d/1LC2MgT9mUQK0Yo9hsI4lWqaTXHWAkSNxyBKWGAqHqe8/edit">Molecular_viz_vtk</a>.
In addition to the document, I read some research papers recommended by my mentors to understand some other (and potentially better) methods of ribbon visualization. 
Tried to implement vtkProteinRibbonFilter usage without using vtkPDBReader but was unsuccessful in this endeavour.
</p>
<h2>What is coming up next week?</h2>
<p>Three goals for next week - 
<ol>
  <li>Implement vtkProteinRibbonFilter usage without using vtkPDBReader.  </li>
  <li>Make a class for vtkMolecule which can store molecular data and pass it on to different function for rendering purposes.</li>
  <li>Read papers on surface model.</li>
</ol>
</p>
<h2>Did you get stuck anywhere?</h2>
<p>Implementing vtkProteinRibbonFilter usage without using vtkPDBReader by using a vtkPolyData has confounded me for some time now. Gotta do it this week somehow.</p>
