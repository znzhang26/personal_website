---
title: "Tensegrity-Constrained Deployable Controls"
description: "Independent Research (2019)"
pubDate: "Aug 15 2019"
heroImage: "/post_img.webp"
---
<div class="py-2">
    <text class="text-lg">
        <b>Keywords</b>: 3D printing, fabrication, functional inflatables</br>
        <b>Patent</b>: Kim, W., et al. (2021). Internally tensioned inflatable structures. U.S. Patent No. US11084541B2. United States Patent and Trademark Office. <a href="https://patents.google.com/patent/US11084541B2/en" target="_blank"><u>https://patents.google.com/patent/US11084541B2/en</u></a></br>
        <b>Conference Presentation</b>: Luntz, J., et al. (2019). Tensegrity-constrained inflatables: A new approach. In <a href="https://event.asme.org/Events/media/library/resources/smasis/SMASIS-Final-Program.pdf" target="_blank"><u>ASME 2019 Conference on Smart Materials, Adaptive Structures and Intelligent Systems, SMASIS 2019</u></a>. American Society of Mechanical Engineers (ASME).</br>
        </br>
        <b>Goal</b>: This project aims to develop a lightweight, compact and inexpensive inflatable tensegrity structure which can be designed with desired compliance or rigidity in select degrees of freedom.</br>
        </br>
        <b>Architecture</b>: The architecture shows how the prototype is built in details. The blue end caps are rigid with multiple attachment points for the internal strings. The strings are arranged to provide partial structural constraints, which can be either tie to the attachment points or threaded through them with low friction to allow additional motion. The transparent tubular membrane is made from soft flexible material, which is sealed to the end caps and enables the bladder to be inflated, where the bladder has extra folded material at the bottom to avoid restricting motion.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig1.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Operation</b>: Take Double Loop Configuration as an example. At the original state, the bladder is deflated. Meanwhile, the upper-end cap is flush to the surface. As the bladder gets inflated, it deploys and all the internal strings become tight. In this case, the strings strongly restrict the axial motion, where it requires a certain threshold of force to cause any deformation. This is because the full internal pressure is supposed to be overcome to make the tight strings go slack. However, the strings in this case do not restrict shearing or bending in one direction.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig2.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Fabrication</b>: The blue end caps and the internal springs/coils are both built by 3D printer but using different materials for expected stiffness. The internal strings are tied on the optical table for equal length. Since the print materials are able to melt together when heating, we use 3D printing pen to fix the spring/coil on the end caps. The next step is to seal the tubular membrane on the edge of the caps by using heat iron. For a better appearance, the final prototype is printed in black as shown in the video below.</br>
    </text>   
    <video width={300} height={300} controls>
        <source src="/project_2019_tensegrity_video1.mp4" type="video/mp4">
    </video>
</div>
<div class="py-2">
    <text class="text-lg">
        <b>Tensegrity Architectural Configuration</b>: The video shows five different configurations ranging from more constrained to less constrained. The fully constrained configuration has a full truss of strings, which when tight constrains all the motions-axial, bending, torsion and shearing. If you try to move it in any direction, you need to overcome the full internal pressure and make one or more strings go slack. The second one has only four straight strings which constrains axial and bending motions but allows torsion and shearing. The third configuration adds threading to the Four Straight Strings which additionally allows free bending motion in one direction. The fourth configuration is a single tripod which constrains axial and shearing but allows bending and torsion. And finally, single string constrains only axial motion.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig3.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Rigidity & Load Bearing</b>: All configurations constrain axial motion and therefore rigidly support axial force. Rigid constraint allows little to no deformation under load up to a threshold.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig4.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Deploy/Stow</b>: Integrated internal coil/waveform spring maintains endcap alignment during deploy/stow, which doesn’t constrain the motion but helps pose the upper-end cap into position when stowing.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig5.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Experiment Settings</b>: All the motions are measured by the test apparatus showing below. I took photos for recording the displacement when adding weights on the prototypes. Picture below shows how the bending motion is measured.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig6.png"/>
<div class="py-2">
    <text class="text-lg">
        <b>Experimental Validation</b>: All configurations exhibit constrain and/or increase stiffness in expected constrained degrees of freedom with lower stiffness and/or free motion in expected unconstrained degrees of freedom.</br>
    </text>   
</div>
<Image class="text-img" format="webp" width={300} height={300} src="/project_2019_tensegrity_fig7.png"/>
