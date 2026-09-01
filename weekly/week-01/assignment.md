# Week 1: Literature Orientation and Actuation Assessment

## Objective

Build a shared technical vocabulary for modular robot docking, understand how origami geometry can create locking behavior, and assess whether pneumatic actuation is a suitable trigger for deploying and releasing a compact origami locking mechanism.

The goal is not to select a final connector concept during Week 1. The goal is to identify design requirements, evaluate published evidence, and define the questions that should guide later mechanism development.

## Part 1: Modular Docking Landscape

### Required Paper

G. Liang, D. Wu, Y. Tu, and T. L. Lam, "Decoding modular reconfigurable robots: A survey on mechanisms and design," *The International Journal of Robotics Research*, 2025. [Publisher](https://doi.org/10.1177/02783649241283847) | [Open version](https://arxiv.org/abs/2310.09743)

### Task

Summarize the general design challenges of docking and locking mechanisms for modular robots, particularly homogeneous modules with identical docking faces. Select three connector examples that you find most relevant or interesting. For each example:

1. Explain the working principle.
2. Identify the main advantages and limitations.
3. Describe one design insight that may be transferable to this project.

### Expected Output

- A short synthesis of the general docking and locking challenges.
- A comparison table containing the three selected connector examples.
- A short explanation of why these examples were selected.

## Part 2: Origami Locking Mechanism

### Required Paper

S.-J. Kim, D.-Y. Lee, G.-P. Jung, and K.-J. Cho, "An origami-inspired, self-locking robotic arm that can be folded flat," *Science Robotics*, 2018. [DOI](https://doi.org/10.1126/scirobotics.aar2915)

### Task

Explain how the origami geometry produces locking behavior and what benefits the authors claim. Identify which models, experiments, and quantitative results support those claims, as well as which important properties remain untested. Finally, discuss which aspects are transferable to an inter-module locking interface and which are not.

Organize the response under the following headings:

1. Claimed advantages
2. Supporting evidence and reported performance
3. Missing evidence or insufficiently tested properties
4. Applicability to the current project
5. First-order estimate of a relevant force, moment, stiffness, or actuation requirement, where the paper provides sufficient information

Clearly distinguish the authors' evidence from your own interpretation.

## Part 3: Pneumatic-Origami Compatibility

### Seed Paper

C. Liu, A. Orlofsky, C. D. Kitcher, and S. M. Felton, "A self-folding pneumatic piston for mechanically robust origami robots," *IEEE Robotics and Automation Letters*, 2019. [Author PDF](https://samfelton.net/paperfiles/Liu_RAL19.pdf) | [DOI](https://doi.org/10.1109/LRA.2019.2895881)

### Optional Starting Point

S. Zare, A. Spaeth, S. Suresh, and M. Teodorescu, "Modular self-lock origami: Design, modeling, and simulation to improve the performance of a rotational joint," 2024. [DOI](https://doi.org/10.1177/14644193231216263)

### Task

Conduct a focused literature study to determine whether, and under what conditions, pneumatic actuation is suitable for deploying and releasing a compact origami locking mechanism. Compare pneumatic actuation with at least two alternative approaches using the following criteria:

- Available force or moment
- Stroke or angular displacement
- Folded thickness and integration volume
- Actuator and support-system weight
- Response time
- Energy required during transition and while holding the locked state
- Controllability and sensing requirements
- Fabrication and integration complexity
- Cycle life, fatigue, leakage, wear, and other likely failure modes

Do not assume that pneumatic actuation is the correct solution. State the conditions under which it is attractive and the conditions under which another actuator would be preferable.

### Expected Output

- Six to ten relevant references, including the seed paper.
- One actuator comparison table.
- A preliminary evidence-based recommendation.
- Two or three unresolved questions that require prototype testing.

## Submission

Complete [`student-response.md`](student-response.md) before the first weekly project meeting. Add newly identified papers to [`../../references/reading-list.md`](../../references/reading-list.md).
