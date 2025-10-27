<h1>URDF & xacro using macros files</h1>
<hr>
<h2>What are <code><b>URDF</b></code> files?</h2>
<ul>
    <li>Stands for <b>Unified Robot Description Format</b></li>
    <li>Used to describe the following:</li>
    <ul>
        <li>The robot's components which can be mainly refered to as <code><b>link</b></code>:</li>
        <ul>
            <li>Spheres</li>
            <li>Boxes</li>
            <li>Cylinders</li>
        </ul>
        <li>The robot's <code><b>joint</b></code> between its components</li>
        <li>Describe the robot's control part parameters such as:</li>
        <ul>
            <li>mass</li>
            <li>inertia parameters</li>
        </ul>
    </ul>
</ul>
<hr>
<h2>What are <code><b>xacro</b></code> files?</h2>
<ul>
    <li>Another type of files made to support <code><b>URDF</b></code> structuring</li>
    <li>Used to simplify <code><b>URDF</b></code> files</li>
    <li>HOW?</li>
    <ul>
        <li>By the use of <code><b>macros</b></code></li>
    </ul>
    <li>What are <code><b>macros</b></code>?</li>
    <ul>
        <li>They are like defining functions that contains one part of the <code><b>URDF</b></code> file which is used more than once</li>
        <li>They are defined and referenced in <code><b>xacro</b></code> files</li>
    </ul>
</ul>
<hr>