<h2> Welcome to my GSoC Blog! </h2>
Hi all! 
I'm Sajag Swami, a sophomore at Indian Institute of Technology, Roorkee. I will be working on adding a new functionality to FURY which shall enable users to visualise various types of proteins via different representations like Richardson aka Ribbon diagrams and molecular surface diagrams. 
<p></p>
As a part of my stretch goals, I’ll try to expand protein diagrams via other representations including -
<ul><li>Stick</li>
<li>Ball and stick</li>
<li>Wire</li>
<li>Pipes and Planks</li>
<li>Sphere</li></ul>
<h2>What did you do during the Community Bonding Period?</h2>
<p>
I had weekly meetings with my mentors and other core team members. In the first meeting I got acquainted with the team members and learnt about the project and its goal/vision. In the later meetings we discussed about various representations of proteins and how to go about implementing them in FURY. We discussed about various libraries which can be used to parse PDB and PDBx files. I made a <a href="https://docs.google.com/document/d/1mSoAWyXlLNrCa3hN-hiP35Lj7rURYMk5jFnWZbZp70s/edit">doc</a> for the same to list pros and cons of using each library. I worked upon my <a href="https://github.com/fury-gl/fury/pull/404">previous PR</a> too during the community bonding period and fixed its docstring syntax.
</p>
<p>
As my college ended early courtesy covid, I had extra time during which I experimented and learnt more about PDB and PDBx files - the details they contain and how to parse them. A small backbone visualisation  of 1mb0 protein made on FURY by extracting coordinate data of its alpha carbons - 
<br>
<img alt="https://github.com/SunTzunami/gsoc2021_blog_data/blob/master/visuals/week1_backbone.png?raw=true" src="https://github.com/SunTzunami/gsoc2021_blog_data/blob/master/visuals/week1_backbone.png?raw=true"> 
</p>
<h2>What is coming up next week?</h2>
I have two major goals for the next week - 
<ul>
<li>Make an actor for the space filling model of the proteins and make PR for the same which will also include the unit tests and a small tutorial for the users.</li>
<li>Try understanding the documentation of ProteinRibbonFilter which will prove beneficial for generating Ribbon diagrams.</li>
</ul>
<h2>Did you get stuck anywhere?</h2>
I was having difficulty when dealing with large protein structures (how to visualise them) as it gets computationally taxing to render many molecules. FURY team was pretty helpful and instructed me to use shaders (luckily for me, the shader in question had been implemented by the community members). This resolved the issue of dealing with large files to a great extent.
