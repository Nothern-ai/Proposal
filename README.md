# Proposal

# Enhancing Genshin Impact with Custom Weather Effects

## Team Members
- Nothern
- Kingsley Situ
- Mengjun Wen
- Jaxon Zeng

## Summary
In this project, we aim to create an immersive environmental enhancement within Genshin Impact, leveraging the ReShade shader framework to introduce dynamic weather effects.

## Problem Description
### Scene Design and Code Integration
We need to design new scenic effects within the existing shader framework of Genshin Impact, involving the search for or development of corresponding effect codes. It is essential that these new codes seamlessly integrate into the Genshin Impact shader, adapting to the current code framework while ensuring compatibility with the overall style and performance requirements of the game.

### Rendering Pipeline Modification
To successfully incorporate these virtual scenic effects into the game, we must deeply understand and modify the rendering pipeline of Genshin Impact, especially the modules that handle scene rendering. This adjustment aims to support new environmental effects while ensuring no adverse impact on the game's performance.

## Goals and Deliverables
### Must Achieve Goals (Baseline Plan)
- **Scene Enhancement Implementation:** Achieve new environmental effects in the Genshin Impact game by modifying and extending codes and rendering pipelines. The original shader performs overall scene rendering, and our goal is to add more detail and effects on a rendering scene prototype, such as the dynamic changes of fog and the phase simulation of solar eclipses.
  - For foggy weather, the current plan is to find a fog generation framework with satisfactory effects, modify and adapt it for Genshin Impact, or alter the shader program to simulate the scattering effects of light. Initially, the scene is rendered normally, and then the fog effect is applied to the rendered image, simulating the interaction between light and fog.
  - The solar eclipse simulation involves applying a red-black filter to parts of the scene. The light source can also be dynamically adjusted.
- **Performance and Compatibility Assessment:** Ensure that the added scenic effects do not significantly impact the game's performance and test compatibility across different hardware configurations to guarantee that most players can experience the improved effects. We will mainly monitor the framerate during gaming.
- **Effect Showcase:** Produce a video demonstration showcasing the new environmental effects in various game scenes and their enhancement of the game's visual experience and immersion.

### Aspirational Goals
- **Additional Environmental Effects:** Should progress allow, we aim to implement more environmental effects, such as snow.
- **Dynamic Weather System:** Implement an enhancement environment that automatically adjusts effects based on the in-game time and location.

## Schedule
- **Week 1:** Read the source code and search for more resources.
- **Week 2:** Modify the shader based on our purpose.
- **Week 3:** Test the shader to achieve our goal.
- **Week 4:** Render some scenes for our final result, and formulate the final report, we plan to use GitHub pages or WordPress to build a website and present the report.

## Resources
- [sefinek24/Genshin-Impact-ReShade](https://github.com/sefinek24/Genshin-Impact-ReShade): The best and safe mod for Genshin Impact with 3DMigoto, ReShade, custom graphics presets, FPS unlock, own launcher and more! 😻✨
