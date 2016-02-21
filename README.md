# Open-Source Laser

##### Colin Ho, Jon Gonzales, Martin Cowell, Amy Liao, Christine Gregg

The goal of this project was to develop an open-source, low-cost laser project capable of projecting industry standard ILDA (International Laser Display Association) image files. 
Laser projectors are typically used for theatrical and stage lighting to project vector graphics or produce lighting effects. 
Since laser projectors use a collimated light source that does not defocus or lose intensity with distance, they are perfectly suited for long range projection applications that would otherwise require very large and expensive long throw projectors. 
As an example, a low-cost laser projector could be used to projection bomb buildings with text and motion graphics for mass communication during public demonstrations. Developing an open-source, low-cost alternative to existing projection bombing methods has the potential to expand people’s ability to reclaim public space and mass communicate ideas.


Our projector operates by redirecting the path of a laser beam using mirrors mounted on galvanometers to trace out thousands of points per second, creating a cohesively projected image. 
The system executes closed loop at 20 kHz and operates using multiple interrupts, necessitating real time and multitasking programming.
