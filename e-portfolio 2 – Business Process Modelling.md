# e-portfolio 2 – Business Process Modelling

## Introduction to Business Process Modelling

Business Process Model and Notation (BPMN) is used to show how a business process works through a diagram. It includes things such as activities, decisions, events, and the people or departments involved in the work (Object Management Group 2014). From what I have learned, one useful part of process modelling is that it puts the steps and responsibilities into one place. This can make a process easier to understand compared with reading a long written explanation. It can also make problems in a process easier to notice and give an organisation a basis for thinking about possible improvements (ABPMP International 2019). In this e-portfolio, I discuss some BPMN concepts, modelling tools and examples, along with what I learned from each artefact.


## Core BPM Concepts Related to Business Process Modelling

There are several concepts that are related to business process modelling. These include end-to-end visibility, standard notation, transparency, AS-IS and TO-BE modelling, strategic alignment, bottlenecks and collaboration. BPMN is useful because it gives people from different areas of an organisation a common way to represent and discuss a process (Object Management Group 2014). An AS-IS model represents how a process is currently being carried out. A TO-BE model represents how the process could work in the future.

I learned that modelling is not just about writing down the steps of a process. When the steps are shown in a diagram, delays, repeated work and unnecessary handoffs can sometimes be easier to see. These problems may be harder to notice when the process is only explained in a meeting or written as instructions. A visual model can also give different departments something they can look at together when discussing possible changes (ABPMP International 2019).



## Artefact: BPMN Basics (YouTube Video)

## Summary
The BPMN tutorial introduced some of the main symbols used in BPMN diagrams. It explained events, activities, gateways, pools and lanes, and showed how these elements can be used together to represent a process. I found the section on gateways useful because gateways can change the direction of a process when a decision needs to be made.

Another point from the tutorial was about automation. Before a process is automated, it is important to understand how the process currently works. If the original process already has problems, automation by itself may not fix them. Drawing the process first gives people a chance to look at what is happening and decide whether changes are needed before automation is added.


## Reflection
When I first started learning BPMN, I found some of the symbols confusing. There were quite a few of them, and I did not always understand why one symbol was used instead of another. The video was helpful because I could see the symbols being used in an actual process rather than only reading their definitions.

The explanation of exclusive and parallel gateways was probably the most useful part for me. I understood the difference better after seeing the different paths in the diagram. Before that, I mostly knew what the definitions meant, but I did not have as clear an idea of how they worked in a process.

I also realised that a BPMN diagram needs to be easy for another person to read. Knowing the correct symbols is important, but that is not the only thing that matters. If the diagram is difficult to follow, it is not very useful even if the symbols are technically correct. This relates to the modelling guidelines discussed by Mendling, Reijers and van der Aalst (2010). After watching the tutorial, I felt more comfortable with the basic BPMN elements and had a better starting point for reading a process model.

## Video link: [https://www.youtube.com/watch?v=R1v0uFJwXWc](https://www.youtube.com/watch?v=kE5TIFJ5XfA)

## Methods and Tools for Business Process Modelling

There are different ways to model a business process, and software can be used to create BPMN diagrams. SAP Signavio and Bizagi are examples of tools that support BPMN elements such as events, activities and gateways (SAP n.d.-a). However, the software alone cannot always show how a process actually works in practice.

The people doing the work can provide information that might not appear in a diagram. For example, employees can be interviewed, the work can be observed, or workshops can be used to discuss the process (ABPMP International 2019). I also learned about process mining, which uses event data to examine how a process is actually being carried out (vom Brocke et al. 2021). These methods provide different types of information, so using more than one approach can give a better picture of a process and its problems.


## BPMN Best Practices (Scholarly Article)

## Summary
Mendling, Reijers and van der Aalst (2010) discuss seven guidelines for creating better process models. The article looks at how the structure of a model can affect its quality, how easy it is to understand and the chance of errors occurring. One idea I noticed was that adding more information does not automatically make a model better.

If a diagram contains too much unnecessary detail, it can become difficult to understand. The authors therefore focus on things such as structure and readability. This is important for BPMN because a model is not just meant to show every possible detail of a process. It should also make the process easier for people to understand and discuss.

## Reflection
This article changed the way I look at a BPMN diagram. Before reading it, I was mostly thinking about whether I was using the symbols correctly and connecting them in the right way. After reading the article, I started thinking more about the diagram as a whole.

The idea of unnecessary complexity stood out to me. A model can contain correct information but still be difficult to use if there is too much going on. I think keeping a model simple does not mean removing important information. It means making sure that the information included has a reason for being there.

I would also keep this in mind when making AS-IS and TO-BE models. If the two models are being compared, people should be able to see what has changed without having to work through a lot of unnecessary detail. This article therefore gave me a practical point to consider when creating process models.

## Example of Business Process Modelling

An invoice approval process is one example of how BPMN could be used in an organisation. An AS-IS model could show manual checking, different approval stages and handoffs between departments. These steps could create delays and could also make responsibility less clear.

A TO-BE model could show a different way of completing the process. Some decisions could be simplified, while repeated checking activities could possibly be automated. Comparing the two models would give stakeholders a clearer way to discuss what could be changed and what the new process is supposed to achieve.

However, the TO-BE model would not prove that the new process will actually be better. Once the new process is put into use, the results would need to be measured. This would show whether the changes actually reduced delays, improved the process or achieved the expected benefits.


## BPMN Tools (Gartner Report)

## Summary
Gartner's Market Guide for Enterprise Business Process Analysis Tools looks at software used for analysing and modelling business processes (Gartner 2025). I found this report useful because it gave me a broader idea of what these tools can be used for. Before reading it, I mainly thought of modelling software as something used to create process diagrams.

The report shows that some tools offer features beyond basic modelling. Depending on the product, these can include process mining, decision modelling, simulation and value-stream mapping. These features can be useful when an organisation wants to understand and analyse a process rather than only document it. I also learned that there is not necessarily one tool that is best for every organisation. The choice depends on what the organisation needs the software to do.



## Reflection
This artefact changed the way I think about process modelling software. I used to mainly see these tools as something for drawing BPMN diagrams. I had not really considered how some of them could also be used to analyse a process.

Simulation was the feature I found most interesting. It can be used to examine things such as cycle time, resource use and bottlenecks (SAP n.d.-b). This helped me see that a process model can be useful for more than just showing the current process. It can also support analysis of possible changes.

The report also made me think differently about choosing software. I would not simply choose a tool because it is popular or widely used. An organisation should first decide what it needs and then compare the available tools based on those requirements. This is especially important when the software will be used for both modelling and analysis.


## BPMN Example (Bizagi Model)

## Summary
The Bizagi example demonstrates a Purchase Request process using BPMN. It uses lanes to represent the different participants, while activities and gateways show the steps and decisions in the process (Bizagi 2023). I found this example useful because it showed how responsibility can be included in a BPMN model.

The example also showed how the process can follow different paths depending on a decision. This was easier for me to understand when I could see the complete diagram. Looking at individual BPMN symbols gives you their definitions, but seeing them together makes their purpose easier to understand.



## Reflection
The Bizagi model helped me connect the individual BPMN symbols with a complete process. The lanes were especially useful because they showed who was responsible for each activity and where the work moved between participants.

The gateways also made more sense to me after seeing them in the example. A written definition can explain what a gateway does, but seeing one used in a real process makes the reason for the decision clearer.

Before looking at the example, I was thinking about BPMN mostly one symbol at a time. After looking at the full model, I started paying more attention to how the elements connect and how the process flows from one activity to another.


## AI Planning, Research and Idea Development Statement

I used AI as a supporting tool while working on this portfolio. I used it to help organise some early ideas, understand BPMN topics and identify possible areas to research. I did not treat the information from AI as automatically correct. For information that was important to my work, I checked it against academic sources and official websites. Information that I could not verify was not used.

AI was most useful for me at the beginning of the work. It helped when I was not sure where to start or when I needed to identify areas that required more research. However, I still had to read the sources myself and check whether the information was accurate and relevant. The final content and reflections were reviewed and edited by me based on what I understood from the sources and artefacts.

## References (Harvard Style)

- ABPMP International 2019, Guide to the Business Process Management Common Body of Knowledge (BPM CBOK®), Version 4.0, Association of Business Process Management Professionals, viewed 4 September 2026, https://www.abpmp.org/page/guide_BPM_CBOK.

- Bizagi 2023, My first model, step by step guide, Bizagi Help, viewed 4 September 2026, https://help.bizagi.com/platform/en/my_first_model.htm.

- Gartner 2025, Market Guide for Enterprise Business Process Analysis Tools, Gartner, 28 October, viewed 4 September 2026, https://www.gartner.com/en/documents/7124830.

- Mendling, J., Reijers, H.A. & van der Aalst, W.M.P. 2010, ‘Seven process modeling guidelines (7PMG)’, Information and Software Technology, vol. 52, no. 2, pp. 127–136, https://doi.org/10.1016/j.infsof.2009.08.004.

- Object Management Group 2014, Business Process Model and Notation (BPMN), Version 2.0.2, Object Management Group, viewed 4 September 2026, https://www.omg.org/spec/BPMN/2.0.2.

- SAP n.d.-a, Business Process Modeling and Notation (BPMN), SAP Signavio Process Modeler User Guide, viewed 4 September 2026, https://help.sap.com/docs/signavio-process-modeler/user-guide/bpmn.

- SAP n.d.-b, Simulating BPMN Models, SAP Signavio Process Modeler User Guide, viewed 4 September 2026, https://help.sap.com/docs/signavio-process-modeler/user-guide/simulating-bpmn-diagrams.

- vom Brocke, J., Jans, M., Mendling, J. & Reijers, H.A. 2021, ‘A five-level framework for research on process mining’, Business & Information Systems Engineering, vol. 63, pp. 483–490, https://doi.org/10.1007/s12599-021-00718-8.
