### competing questions
- does estrogen use lead to endometrial cancer
- does estrogen use speed up the rate of endometrial cancer diagnosis
### chain
- DAG: directed acrylic graphs. a DAG is about how the world works
- example of a hypothesis about reality:
![alt text](cause-and-effect.png)
- association: suppose we can collect the data below:

| lead ninja | pocari sales |
|------------|------------|
| low        | low        |
| medium         | medium         |      
| high         | high         |      

![alt text](association.png)
DAGs could produce the same data => DAG is both a causal and statistical model
- interventions follow arrow path => mandating all lead ninjas to wear bikinis to work tmr won't cause pocari to bankrupt
- arrow =/= deterministic
- no arrow = no causal relationship, though there might still be associations
### fork: common causes
- systenmatic bias: any association between A and Y not due to the effect of A on Y
- common causes create an association
- conditional independence:
![](conditional-independence.png)
- listing down all mediators (B, C, etc) is unnecessary when you're trying to to estimate total causal effects of variable A on variable Y
### collider: conditioning on common effects
- common effects don't create an association, but can create an inverse association => selection bias
- common effects without condition:![alt text](common-effects-without-cond.png)
- common effects with condition: ![alt text](common-effects-with-cond.png)
  - either A or Y can be an indirect cause of S

### sidenotes
one thing that's been bugging notetaker is that Miguel keeps openinig each example with sth along the lines of "we use expert knowledge to draw this graph, but you could also come up with it through data", but like where does his "expert knowledge" come from, does it not come from synthesized theory repeatedly falsified through better data?
