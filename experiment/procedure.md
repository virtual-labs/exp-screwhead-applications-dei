<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 2: Procedure</title>
    <link rel="stylesheet" href="css/main.css">
</head>
<body>

    <h2>Experiment Procedure: Screw Head Forming</h2>
    
    <p>This procedure outlines the steps to analyze the <b>Cold Heading</b> process for different fasteners using the Virtual Lab simulations. Follow these steps to correlate theoretical parameters like Lead, Pitch, and Strain with the visual results.</p>

    <hr>

    <h3>Step 1: Machine and Billet Selection</h3>
    <p>Before starting the simulation, identify the material properties. The billet used is <b>Plain Carbon Steel</b> at an ambient temperature of <b>20°C</b>. 
    <br><br>
    <b>Action:</b> Play the <b>Bolt Setup</b> or <b>Hexagonal Bolt Setup</b> video. Observe how the cylindrical rod is positioned within the lower die before the mechanical press begins its stroke.</p>
    

    <h3>Step 2: Observing the Heading Operation</h3>
    <p>Heading is an upsetting process used to produce a larger cross-section at the end of a rod. 
    <br><br>
    <b>Action:</b> Watch the <b>ScrewHead Setup</b> video. Note that while industrial screw forming usually takes two steps, this simulation simplifies it into a single downward stroke. Observe the upper die (punch) compressing the billet into the die cavity to form the slotted head geometry.</p>

    <h3>Step 3: Analyzing Material Deformation (Strain)</h3>
    <p>As the mechanical press applies force, the metal deforms plastically. This is where the theory of <b>Grain Refinement</b> comes in; higher strain leads to better mechanical strength.
    <br><br>
    <b>Action:</b> Play the <b>Bolt with Strain</b> and <b>Hexagonal Bolt with Strain</b> videos. Watch the color-coded mesh. The transition from blue to red represents the increase in equivalent strain as the billet takes the shape of the die.</p>
    

    <h3>Step 4: Quantifying the Results</h3>
    <p>To understand the force required for different head shapes, we must analyze the relationship between the tool position and the resulting strain.
    <br><br>
    <b>Action:</b> Refer to the <b>Hexagonal Bolt with Strain</b> video. Observe the graph plotted between <b>Punch</b> and <b>Pilot Height</b>. 
    <ul>
        <li>Identify the peak strain value (e.g., 3.21625 for Hexagonal vs 3.36107 for Screw Head).</li>
        <li>Note how the strain is highest at the corners of the hexagonal head where the material is forced to fill the die edges.</li>
    </ul></p>

    <h3>Step 5: Verifying Thread Parameters (Theoretical)</h3>
    <p>Once the head is formed, the next industrial step (Thread Rolling) defines the <b>Pitch</b> and <b>Lead</b>. 
    <br><br>
    <b>Action:</b> Based on the final billet shape seen in the <b>ScrewHead Setup</b>, calculate the theoretical Lead for a "Double Start" thread if the Pitch were 1.5mm (Lead = Pitch × Starts).</p>
    

    <hr>
    
    <div style="background-color: #e8f4fd; padding: 20px; border-radius: 8px; border: 1px solid #b3d7ff;">
        <h4 style="margin-top:0;">Summary for Observations:</h4>
        <ol>
            <li>Observe the initial billet mesh.</li>
            <li>Run the heading simulation.</li>
            <li>Record the maximum strain from the "with Strain" videos.</li>
            <li>Compare the final head geometry with the "Types of Screws" discussed in the Theory section.</li>
        </ol>
    </div>

</body>
</html>
