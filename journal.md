# VoltWay — My Development Journal

**Project:** Turning Road Heat into Useful Electrical Energy  
**Working period:** October 10–November 4, 2026; refinement on November 23–26, 2026  
**Total time:** 62–81 hours  

## About VoltWay

I developed VoltWay for the Emirates Young Scientist Competition and with the goal of pursuing a patent in the UAE. My idea is to recover some of the heat flowing through sun-warmed pavement using thermoelectric generators, with a passive heat-transfer path toward cooler soil.

This is a retrospective account of my research, design, documentation and presentation work. The sections group related work across the project period; they do not mean I spent every day in a date range on only one task.

## October 10–November 4 — Research and project development

### Researching the problem and the conversion principle

My starting point was the heat absorbed by roads and whether some of that energy could support local roadside equipment. I developed the research question around the relationship between temperature difference and electrical output, rather than road temperature alone.

The research in my proposal covers the Seebeck effect, thermoelectric generation and the distinction between a Peltier module used for demonstration and a purpose-built generator. I used these principles to define what the project would need to measure.

`ΔT = T_hot − T_cold`

`V_oc ≈ S_eff × ΔT`

A key distinction in the research is that open-circuit voltage is not the same as useful power. The electrical load, internal resistance and heat-transfer conditions all affect what a module can deliver.

### Developing the heat-transfer architecture

I developed the proposed system around three main parts: an upper heat spreader, a thermoelectric module and a lower conductive path toward cooler soil. The upper interface needs to transfer heat while protecting the module; the lower interface needs to carry heat away so a temperature difference can be maintained.

I considered soil depth, moisture, thermal contact and local soil warming as factors that could affect performance. Passive cooling is a design objective, but its effectiveness needs outdoor testing.

### Separating the exhibition model from the road design

I defined a small demonstrator using a controlled heating pack, a single thermoelectric module and a heat sink. This gives the project a practical way to investigate the conversion principle before attempting a pavement installation.

The road-unit concept uses pavement heat instead of the heating pack and a subsurface conductor instead of the air-cooled sink. I documented the additional constraints that come with this change: traffic loading, compaction, moisture, corrosion, electrical isolation and maintenance access.

### Planning experiments and data analysis

I developed a measurement procedure that includes both module-face temperatures, open-circuit voltage and loaded voltage across a known resistor. The plan includes repeat measurements and time for readings to stabilise.

`I = V_load / R`

`P = V_load² / R`

I included a results-table format and planned graphs comparing temperature difference with voltage and power, along with temperature changes over time. This gives the project a clear method for evaluating performance rather than relying on a voltage reading alone.

### Developing electrical collection and energy management

I worked through the proposed path from individual modules to power-conditioning electronics, roadside storage and connected loads. The proposal considers series/parallel collection and the effect of different modules operating at different temperatures.

For control, I included monitoring generator voltage/current, battery state and module temperatures. A light sensor can provide context, but it cannot establish generated power. I also accounted for the fact that a voltage booster introduces losses and cannot create additional energy.

### Assessing feasibility and future applications

I considered hardware, installation, maintenance, storage replacement and road durability as parts of the feasibility question. I included a planning equation for daily energy:

`E_day = N × P_avg × t_effective × η_system`

The inputs need measured performance before the equation can support a deployment decision. I focused the initial application on appropriately sized roadside sensors and monitoring equipment. Larger facilities and EV-charging support remain longer-term goals.

### Writing the proposal and preparing presentation materials

I brought the research and design into a structured engineering proposal covering the problem, operating principle, architecture, experiment plan, limitations and development roadmap.

I also worked on the **PowerPoint presentation, project poster and video**. These were part of the same project workload. They helped me communicate the problem, explain the heat-transfer path and present the relationship between the exhibition model and the proposed road system.

## November 5–22 — Break from project work

I did not log project work during this period as I had half yearly exams

## November 23–26 — Refinement and feedback

I returned to VoltWay for **3–4 hours each day** to refine the project and seek advice from people and mentors.

This stage focused on reviewing the explanation, strengthening the research and engineering narrative, and improving how I communicated the project. I revisited the proposal and presentation materials with attention to clarity, technical reasoning and the next steps needed to develop the idea.

The refined account keeps the proposed design clear while separating it from performance that still needs measurement. The research document does not contain completed numerical test results, so this journal does not add any.

## Working hours

My regular schedule during October 10–November 4 was **2–3 hours each Monday–Thursday** and **5 hours total across Friday–Sunday**. During November 23–26, I worked **3–4 hours per day** on refinement and feedback.

| Work period | Hours |
| --- | ---: |
| October 10–November 4: 15 school days at 2–3 hours | 30–45   |
| Weekend work during that period: four weekends at 5 hours total each | 20 |
| November 23–26: four refinement days at 3–4 hours | 12–16 |
| **Total project time** | **62–81** |

My supervising teacher reviewed and confirmed the time I spent on the project. The total includes research, design, proposal writing, PowerPoint, poster, video and refinement work. The range reflects the different session lengths in my reported schedule.

## What I learned and what comes next

Developing VoltWay showed me that the thermal pathway matters as much as the generator. A useful design needs sustained heat flow, appropriate electrical loading and a realistic account of losses and operating conditions.

The next technical steps are to document the actual build, confirm the exact module and its datasheet, collect repeatable measurements and use the results to refine the thermal and electrical design. An outdoor pilot would then need additional mechanical protection and civil-engineering input.

My patent objective remains a goal; this journal does not claim a granted patent. If all goes well, I'll aim for applying for a patent!

