---
title: "MAE 3780 Mechatronics Robot Project"
excerpt: "A team-based mechatronics project focused on designing, building, coding, and testing an autonomous cube-collecting robot."
image: /assets/images/mechatronics-robot.jpg
---

# MAE 3780 Mechatronics Robot Project

## Project Overview

For my MAE 3780 Mechatronics final project, my team designed and built an autonomous robot for a one-minute cube-collecting competition. The goal of the competition was to gather as many cubes as possible within the robot’s perimeter before time ran out.

Our robot was designed to be simple, lightweight, and reliable. Since cubes counted as long as they were completely inside the robot’s boundary, we focused on creating a structure that could guide cubes into the robot and keep them contained. The robot used cardboard walls around the back and sides of the chassis, along with a V-shaped cardboard piece at the front to funnel cubes toward the side openings. Once cubes entered those spaces, the surrounding walls helped keep them inside the robot’s perimeter.

For sensing and control, we used a color sensor to detect the black border of the playing field. When the robot detected the black boundary, it stopped, backed up, turned away from the edge, and continued driving. Since we did not use sensors to detect cubes directly, our strategy was based on covering different areas of the board and changing direction when the robot reached the border.

## My Contribution

I contributed to the mechanical design, construction, wiring, testing, and troubleshooting of the robot. I helped significantly with constructing the final chassis and mounting the necessary components. I also helped make sure the wiring was correct and that the robot’s code worked properly for the competition.

During the project, I helped test different cardboard wall shapes, attachment methods, and design ideas. A major part of our design process was figuring out how to keep cubes inside the robot’s perimeter while the robot moved and turned. I also contributed to the final report by helping explain the robot’s design, competition strategy, performance, and areas for improvement.

## Design Process

At the beginning of the project, our team considered more complicated intake ideas, including a sweeping arm and a rotating mechanism. After testing and discussing the design with the TAs, we decided that a simpler cube-collection system would be more reliable. Instead of using extra moving parts, we focused on driving into cubes and guiding them into the robot’s perimeter.

We tested several cardboard shapes, wall heights, and attachment methods. We eventually found that taller cardboard walls and a simple V-shaped front helped guide cubes into the robot while keeping the structure stable. We also used larger wheels and adjusted the robot’s design so it could move more effectively during the competition.

## Competition Performance

Our robot performed well during testing, but we ran into reliability issues during the actual competition. The robot was able to collect cubes and had a simple strategy that worked in testing, but some parts of the chassis and sensor mount were not as secure as they needed to be. Because we relied heavily on tape and cardboard, the robot became less reliable under competition conditions.

One thing we would change is how we used our budget. We could have used more of it to 3D print parts of the chassis or create a more secure mount for the color sensor. This would have made the robot stronger and more consistent during the final competition.

## What I Learned

This project taught me that a simple design is often better than a complicated one, especially when reliability matters. I learned how important it is to test early, make the chassis sturdy, secure sensors properly, and avoid adding unnecessary mechanisms that can make the robot harder to control.

I also learned that competition strategy matters just as much as the physical design. If we could do the project again, we might focus more on speed and driving quickly toward the center of the board at the start of the match. Overall, this project helped me better understand how mechanical design, electronics, coding, testing, and teamwork all come together in a real mechatronics system.

## Final Report

<a href="{{ "/assets/MAE_3780_Final_Report.pdf" | relative_url }}" target="_blank">View Final Report PDF</a>