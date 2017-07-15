# Project Title
NetAI


## Abstract / Purpose 
To generate dynamic graph from configuration management tool configuration like puppet.


### Description
Organization manages there infrastructure configuration using tools like puppet, chef & ansible. It is difficult to understand 
the relation among different application, nodes, virtual machine, database connection etc. If something goes wrong with single application or virtual machine etc
It is difficult to understand the impact, when something fails who it is going to impact other infrastructure. 
eg: 200 puppet modules are using by different team for managing entire infrastructure. 
 

Requires an intelligent algorithm to parse the static puppet configuration & build relations among each other & generate a visual graph.
Visual tool can be display each application, virtual machine, database, load balancers etc in some graph nodes & connections are displayed by edges. 
This node can be connected to monitoring tools like nagios, network monitoring tools to display real time monitoring 
on the visual graph. Once the monitoring start alerting, it should be reflected in the visual graph.



### Prior knowledge required
- [ ] understanding of ruby because puppet is written using ruby
- [ ] puppet
- [ ] Basic understanding of Machine learning (Supervised & un-supervised learning)
- [ ] Basic understanding of Artifical intellegence (Like bayes theorem, hide-markov model)
 


### Tools & Technology
- [ ] Any


Reference | Links
------ | ------
puppet | [https://puppet.com/product/how-puppet-works](how puppet works)



#### Are you willing to be the mentor to this problem statement *Technically* or *Non-Technically* ?
- Yes 
- Both



#### Github User Id:
@akoserwal
