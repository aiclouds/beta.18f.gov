## Background

In late 2015, our internal ops team proposed that some staff time be spent integrating various parts of 18F internal processes. The interview process into what needs this would fill provide insight into needs a dashboard for 18F generally might fill. For all the details, see this [internal google doc](https://docs.google.com/document/d/1UaO-EnXzfFiicSDFMhqW0XWuvgeRIKhqrjSrJ_pIWnY/edit).

In short, 18f uses at least five different applications to manage “back office” functions like time keeping, accounting, recruiting / hiring, project intake, project assignments, billing, and other related functions that are critical to 18f’s ability to deliver value to its clients.

Each one of these applications are maintained (in varying degrees) by 18F. For instance, tock is wholly managed by the 18F team; google apps are managed by google and gsa ocio. Each one of the applications has the ability to communicate with other applications or services via their own api’s, though none of the integration between applications has occurred. At present, maintaining multiple, unconnected applications results in duplication of information, lots of human error, and a disjointed experience for all user groups, from line employees to clients to managers.

## Hoped-for Outcomes

**The two most important outcomes:** ability for anyone on the team to understand our projects and who is on what, as well as future intentions.

**For ops team:** looking for dollars and cents, and 1/0s on projects.

**In detail, by user group:**

line employees: as a result of solving the problem, the designers, engineers, technologists, business strategists, researchers, and other employees who supply their talents to our clients and our internal priorities will have much more clarity into what projects 18f is currently working on, the status of those projects, what projects are being considered, and the financial health of the organization. by knowing this information (or even knowing they may easily access this information), line employees will gain a better understanding of the “business” of 18f, be empowered with information about project opportunities when speaking with their colleagues and supervisors, and have to expend less effort to get answers to questions about 18f’s operations. combined, these results should help employees be more productive and happier.

line managers: the employees who manage the line employees (for instance, the head of the engineering team) need up-to-date and on-demand insight into the names and types of projects their teams are working on in order to ensure their team is neither under- or over-worked, and the type of work they are doing aligns with interests and skill sets. as a result of solving the problem, line managers will no longer have parse through duplicate and/or non-standardized records; instead this information would be standardized across applications (this proposal does not include the addition of a reporting tool that would take the output from one or more integrated applications and provided to end users in either preset or manipulable reports / dashboards. functionality like this will likely be proposed at a later date).

project and product managers: the members of our team responsible for delivery a solution to a client or internal problem require accurate and easy access to information about the money and people supplied to their project or product on a regular basis. as a result of solving this problem, that information will be standardized across the various applications that the PM uses, such as accurate project and people names from tock to float to invoices to weekly financial reports generated in google sheets.

business managers: the persons who are responsible for making sure 18f’s business are delivering value to our clients, deciding whether to take on new engagements, or to wind down / ramp up existing engagements require up-to-date, on-demand and easy access to information about the resourcing status of each current engagement (money left on agreement, people assigned to engagements, skills needed and assigned to engagements) as well as the capacity of 18f to take on additional work (opportunities available via the intake process, number and skill types of people on staff or joining 18f in the future). a result of solving the described problem would be to remove uncertainty about the supply and demand attributes that business managers must consider when managing their respective businesses, and in turn, help business managers make more informed decisions about current and future projects.

operations employees: our operations colleagues currently spend a lot of time and energy manually ensuring that data is complete and standardized across the various applications that the organization uses. as a result of solving this problem, data across applications should automatically reconcile with itself (or throw an error if a mistake occurs). this result would allow the operations team to focus on higher value tasks and be more confident in the data they provide to the rest of the team.