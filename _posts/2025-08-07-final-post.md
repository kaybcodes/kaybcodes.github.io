---
layout: post
title: "💻 First Issue to Final Push ✅ "
date: 2025-07-28
---

Eight weeks ago, I came into the Contributor Catalyst Fellowship with a simple but meaningful goal of wanting to learn more about open source. 
Although I had heard the term before and even used open-source tools in class, I didn’t fully understand how open source communities worked or how someone like me could contribute in a real and valuable way. 
My hope was that this program would give me a deeper understanding of what it means to be an open source contributor, both technically and collaboratively. Looking back, I feel that goal evolved into something even bigger.
Not only did I learn what open source is, I also learned how to participate in it by reading through real issues, following community norms, tracing code across large unfamiliar projects, and thinking like a contributor rather than just a user.
Through a mix of challenges, feedback, and team collaboration, I was able to grow both my technical skills and my confidence.

Over the course of the summer, I can confidently say I achieved the goals I set for myself at the beginning of the program.
I became much more comfortable contributing to open source by engaging with real issues, navigating large repositories like processing4 and p5.js, and learning how to approach problems without needing to understand every line of code.
I also developed a stronger grasp of how collaborative GitHub workflows actually function from setting up upstream remotes to working in feature branches and submitting pull requests.
Most importantly, I gained the technical confidence I was looking for. I no longer feel like I’m just observing open source from the outside.
I’ve experienced what it’s like to contribute meaningfully, and I know I can continue to do so.

The processing4 repository is the open-source codebase behind the Processing 4 desktop environment. It’s a Java-based creative coding platform widely used by artists, designers, and educators.
It serves as both an IDE and a graphics framework, enabling users to write visual and interactive sketches with minimal setup.
While it's separate from the p5.js JavaScript library, both projects share a common mission: making creative coding more accessible and expressive across different languages and platforms.

One of the issues we worked on was Issue #981 in the processing4 repository, which focused on modernizing the dxf library’s build process by migrating it from Ant to Gradle using the java-library plugin.
My team and I contributed by modifying the java/libraries/dxf/build.gradle.kts and /java/build.gradle.kts files updating dependencies, and configuring resource handling and build tasks.
We submitted a pull request with these changes, and it’s currently awaiting review and merge.

For Issue #6660, my team updated the conditional logic in output.js to fix an issue with how JavaScript compares arrays.
We removed an unnecessary else if that used strict inequality to compare arrays by value, which doesn’t work as expected in JavaScript.
Replacing it with a simple else block allowed the logic to continue efficiently without relying on a faulty comparison.
Our pull request has been submitted and is currently awaiting merge.

Issue #1190 in the processing4 repository, which caused the debugger to silently fail whenever a sketch’s folder name didn’t match its .pde filename.
That mismatch prevented the debugger from correctly mapping breakpoints to the compiled class, making debugging feel broken. To resolve this, my team submitted PR #1197.
We modified LineBreakpoint.java to allow .pde files to resolve properly even when names differ and added logic in Debugger.java to detect and translate misaligned PDE filenames at runtime.
Our fix ensures that breakpoints now trigger correctly regardless of the folder/name mismatch, and we tested it through both Gradle builds and live debugging.
The pull request is currently awaiting review and merge.

One of the most valuable things I’ve learned through this program is how collaborative and community-driven open source truly is. Before this fellowship, contributing to a large project felt out of reach.
But through pairing with my team, asking questions, and slowly building confidence, I began to understand not just the technical aspects of open source, but also the importance of communication, patience, and shared learning.
Getting feedback from maintainers, debugging in real time, and seeing how even small commits contribute to a bigger mission made it all click.

Now that I've worked on real issues across different repositories, I do feel like I have a strong enough foundation to contribute to new open source projects independently.
That said, I’d love more practice with setting up dev environments and navigating complex build systems. Those parts definitely challenged me, but they’re skills I want to get stronger in.
A mentor who could help guide me through that side of things in future contributions would be a huge plus.

I definitely plan to keep contributing to open source beyond this program. The sense of impact and community is something I don’t want to let go of.
I’m especially interested in continuing work with beginner-friendly projects or documentation anything that helps others get started the same way this program helped me.
I'm also considering joining more open source communities or even starting my own small project to maintain.

Looking ahead, I’d definitely be interested in attending an open source conference. I think it would be a great opportunity to meet contributors in person, explore different kinds of projects, and continue learning from people with all kinds of technical backgrounds.
Being in a space where open source is celebrated and discussed face-to-face feels like the natural next step after this virtual fellowship experience.
I’m curious to see how others navigate their open source journeys and I know I’d leave even more inspired to keep going with mine.



