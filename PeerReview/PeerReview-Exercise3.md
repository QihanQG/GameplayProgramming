# Peer-Review for Programming Exercise 3 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment three: Aegis. To do so, we will give you a rubric to provide feedback. Please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to check the code and project files that the instructor gave out.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

## Due Date and Submission Information
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer review. This review document should be placed into the base folder of the repo you are reviewing in the master branch. The file name should be the same as in the template: `PeerReview-Exercise3.md`. You must also include your name and email address in the `Peer-reviewer Information` section below.

If you are in a rare situation where two peer-reviewers are on a single repository, append your UC Davis user name before the extension of your review file. An example: `PeerReview-Exercise3-username.md`. Both reviewers should submit their reviews in the master branch.  

# Solution Assessment #

## Peer-reviewer Information

* *name:* [Qihan Guan]
* *email:* [qgguan@ucdavis.edu]

### Description ###

For assessing the solution, you will be choosing ONE choice from: unsatisfactory, satisfactory, good, great, or perfect.

The break down of each of these labels for the solution assessment.

#### Perfect #### 
    Can't find any flaws with the prompt. Perfectly satisfied all stage objectives.

#### Great ####
    Minor flaws in one or two objectives. 

#### Good #####
    Major flaw and some minor flaws.

#### Satisfactory ####
    Couple of major flaws. Heading towards solution, however did not fully realize solution.

#### Unsatisfactory ####
    Partial work, not converging to a solution. Pervasive Major flaws. Objective largely unmet.


___

## Solution Assessment ##
### Stage 1 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The shield recharging mechanism works as described in the instructions. When the shield get hit, it enter recharge delay period lasting 'recahrge_delay' seconds. And the shield only recharge at 'recharge_rate' after the recharge delay. It also stops recharging and enter another recharge delay period when being hit during this period.

___
### Stage 2 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
It fulfills every requirement of stage 2. The class implements the exact damage formula specified and takes shield type, projectile type, and projectile damage as inputs and returns the calculated damage  value. The damage type factor table is also correctly implemented with combinations and the values match the provided table.
The class also autoloaded via the Project Settings.
___
### Stage 3.1 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
It also fulfills every following requirement of stage 3:
1. It has a `ShieldFactory` and a `ProjectileFactory` class with the factory design pattern.
    
2. It has a  'ShieldSpec' and 'ProjectileSpec' classes that only hold a specification. And it only has properties and no methods

   shield_spec
   
   https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_spec.gd#L1-L8
    
   projectile_spec
   
   https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_spec.gd#L1-L8
   
4. Both the factory's build classes have a build function that take shield specs.

    shield_factory
   
    https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/shield_factory.gd#L1-L18
   
    projectile_factory
   
       https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_factory.gd#L1-L17

6. Both factory classes has generate_random_shields and generate_random_projectils methods that randomly generate their properties within the stated specification range.

    shield_factory
   
    https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/shield_factory.gd#L21-L43
   
    projectile_factory
   
    https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_factory.gd#L20-L40
   

___

### Stage 3.2 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
It has the correct power limit for power rating:

'projectle_factory.gd'

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_factory.gd#L5

'shield_factor.gd'

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/shield_factory.gd#L5

And the correct formula for power rating:

'projectile_factory.gd'

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/projectile_factory.gd#L43-L44

'shield_factory.gd'

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/shield_factory.gd#L46-L47

And both factories ensure the randomly generated items don't exceed power limits. And from my testing, and it works as intended based on my testing.

___

### Stage 4 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The 'TestFactory' class generates random shield specs using the 'shield_factory' class, and it also generates 5-10 random projectiles using the 'projectile_factory' class.
It sets up a test schedule to manage their firing. It has a separate 'TestSchedule' class that manages the firing sequence while respecting the projectile's charge times. 

It also unbinds your inputs during the testing and has a separate button input for starting the test schedule and randomly generating the shield. The shield's color also correctly matches their type color. And it outputs the appropriate fanfare when the test is over.

There aren't any bugs I noticed during my test so this implementation is perfect.

___
# Code Style #
The code adheres to the style guide of this class. It's well-structured, easy to read. And it follows the factory design pattern. 


#### Style Guide Infractions ####

None that I can find

#### Style Guide Exemplars ####

The "TestFactory.gd" class is very well implemented and structured. It accomplishes what it is supposed to do and you can easily follow the logic from reading the code.

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/test_factory.gd#L1-L65

___

# Best Practices #

The code adheres to the best practices and the coding convention of GDScript, other than some very minor format issues.

#### Best Practices Infractions ####

Minor introductory comment placement error, placing it right below the class definition:

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/shield_spec.gd#L1-L3

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/test_factory.gd#L1-L4

The introductory comments should be placed above the class definition.


#### Best Practices Exemplars ####

It has insightful and concise comments for all of them throughout classes and scripts. 

The best example is telling you what button inputs to start the test and generates the shields

https://github.com/ensemble-ai/exercise-3-factory-pattern-tdha7/blob/1897fbad53a258d167005bc9807ef91d1ac643ce/aegis/scripts/laboratory.gd#L26-L39

