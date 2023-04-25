# Summary - The Secure Development Handbook


## Chap. 1


- For dummies;
- No connection - always secure (Past 2010);
- Computer network == Security Issues;
- Essential practices for developers;
- Steps;
- Used Experts knowledge;
- Used Trials;


## Chap. 2


- ONLY for this book: (Against attacks) Security == Privacy (User)

  
## Chap. 3 - Incentivization


- Persuade devs. Show the importance;
- Sec isn't taught at university;
- No one cares (expensive, painful);
- Motivate team. Contextualize to their reality;
- Group discussion;

### Incentivization Event

- Agile Security Game; No experts;
- Like a RPG;
- Has a master; Players chose security cards;
- Demonstrate the role of the Product Manager on Security;
- Others: 

### Pen Test Workshop

- Security expert; Tries to invade Software showing it to the Devs;
- Traditional way; Shows the importance;
- Has issues: Security as an adversary; Appear to be just matters of code (design and usability are more important);
- At the start (no code), can't be applied;

### Lectures

- Needs experts;
- Showcase examples and how they were dealt with;

### Talk

- Needs expert; Good for one developer;

### Cardinal Rule - Don't be afraid, but confident. Show that the threats can be dealt with.


## Chap. 4 - Threat assessment 


- What (prioritization, project context) before How;
- Threat modeling - personalized for the team context;
- Manager needs to know.


### Essential way: Brainstorming;

- Circle disposition; Whiteboard;
- Write all threat possibilities listed by devs;
- Consider the attacker profile, what would they do. 
- Consider system architecture and interfaces;
- Create a document;
- Repeat every year.


## Chap. 5 - Risk / Cost Assessment


- Attribution of the PM;
- Needs information on threats (Probability, Cost, Damage if happens).

### Essential: Risk / Cost Workshop

- Take the threats list. Prioritize (low, medium, high) them in group for likelihood, impact if occurs and cost of mitigation;
- Will be inaccurate, but important for organization knowledge;
- Discuss mitigation of each threat in the prioritized order;
- Can be code, new functionalities, processes, person...
- Give story points to each mitigation (or any other form of estimation the devs use in a daily basis).


## Negotiation


- PM needs to trade-off (security has costs);
- Security can't be total (If it's total, you've invested too much);
- PM deals with uncertainty;
- "What will be the problem if we don't implement this?"
- Devs need to inform the PM;
- Cost: Time and money;
- Impact: Description in practical ways (sues, image damage, marketing...);
- Risk: Probability on a time frame.

### Continuous Reminder

- Incentivization doesn't last long;
- Remind every month;
- Reminder session; Talk about the previously considered threats, what was done and can be done;
- Others:

### Positive feedback

- Encourage security initiatives; Give good feedback to people;

### Security competitions

### Use security checklists

### Use recent and notable examples (public disasters)

### Buy or create sec courses or ethical hacking training

### Informal sessions and talks (with food)


## Chap. 7 - Components choice


- No need to see code if you know the components used. Exploit vulnerabilities;
- Search if the component / framework is secure;
- Can have dev costs (time to search for components and assess their security);
- Use vulnerabilities databases (Paid or free);
- Choose reliable suppliers;
- Keep components up-to-date;
- Consider component update costs (may need to change code or insert new errors);


## Chap. 8 - Automated static analysis


- Necessary but insufficient;
- Doesn't guarantee security;
- Can fool devs that the security is guaranteed;


## Chap. 9 - Code review


- Way to include the persons, don't use only tools;
- From an expert: Separate the most important and risky parts of the code;
  - Can be expensive
  - Transfer knowledge from the expert to the team;
  - Use external people 
- From a third party (commercial):
  - They use a list of issues with mitigations;
  - Search the code for the issues;
- Internal review (code review; pair programming)
  - More practical if there is already a culture;
  - Pair programming increases productivity;
  - Review can be difficult to implement (fear, criticize);


## Chap. 11 - Sec. Champion


- The person who will (know | care) more about security ;
- An organization specialist;
  - From other parts of the organization;
  - From outside;
- Not an expert but a dev that worked on successful secure software;
  - Export the processes used by the projects.
- A normal dev who likes security and will be formed / financed by the company to learn;


## Chap. 12 - Pen test


- External people;
- White hat team;
- Red team - Simulates social engineering for attacks and other sophisticated tools;
- Try to invade the system - Simulate hacker behaviour;
- Hard to find white hats;
- Can be costly;
- Doesn't guarantee security;

