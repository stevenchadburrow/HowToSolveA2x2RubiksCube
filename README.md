# HowToSolveThe2x2RubiksCube

I just figured out how to solve a 2x2 Rubik's Cube, and wanted to share.  A good tutorial link is here:

http://www.rubiksplace.com/cubes/2x2/

If you find that you messed up somewhere, just go back to Step 1.

Step 1: Solve white on one side.

This is the least formulaic step.  I don't know any formulas on how to do it, I just keep playing with it until it works.  Generally I get some whites on one side, but start to change them out until
it's actually solved.  "Solved" means the adjacent colors also match up correctly.  This is the "fun" step, every thing else is just a formula.

Step 2: "Solve" yellow on opposite side.

When your white is solved, there will be one of seven different yellow patterns on the opposite side, which will now be the 'top'.  You want a pattern of yellows that look like:

<code>
    x x
Y | x Y | x
Y | x Y | x
    x x
</code>
    
Where 'Y' is yellow, and 'x' is anything else.   Notice the two yellows on the right of the top, and the two other yellows on the side.  If you do not have that, you need to perform a formula until
you get that particular pattern.  

Hold the cube so that the yellow is on top, the white is on the bottom.  Perform these moves in sequence:

<code>
R U R' U R U2 R'
</code>

R = Right side Clockwise,
R' = Right side Counter-Clockwise,
U = Up side Clockwise,
U2 = Up side twice (half turn)

You will get a different pattern of yellows.  Continue to do the exact same formula until you get that desired yellow pattern mentioned above.   It shouldn't take more than six times, so if it's not working
just rotate the top 90 degrees and try the same formula again a few more times.

When you finally have the yellow pattern you want, the formula to solve the yellow is very simple:

<code>
F R U R' U' F'
</code>

F = Front side Clockwise,
F' = Front side Counter-Clockwise,
U' = Up side Counter-Clockwise

You will now have all of the whites solved, and the yellows on the top.  You will probably not have a completed cube yet, but that's ok.

Step 3: Finishing the cube.

To make the rest work, try to line up as many colors as possible.  Sometimes only one corner is good, sometimes two corners will be good.  If there is only one good corner, I put that corner closest to me
in my left hand.  If two are good, I put a bad corner in that same closest-left-hand position.  It shouldn't matter too much.

Now for the final formula:

<code>
L' U R' D2 R U' R' D2 R2
</code>

L' = Left side Counter-Clockwise,
D2 = Down side twice (half turn),
R2 = Right side twice (half turn)

It might work, it might not.  Repeat the same formula a few times.  When it is completed, it might not just line up perfectly, so make sure to try to line up like colors as much as possible each time to see if you have a completed cube.

Conclusion:

The first part is just playing around, but after you solve one side, formulas are needed.  Repeating the same formulas is not fast, but it's easier to remember.  I haven't found any particular tricks to
make it faster, but that wasn't the object to begin with.  Memorizing the formulas is fairly easy if you do it a lot, and try to do it without looking at the formulas.  I got a hang of it within a couple
of hours.

How do you use this to solve a 3x3 Rubik's Cube?  I have no idea! :)
