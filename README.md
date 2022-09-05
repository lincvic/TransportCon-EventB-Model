# Transport-Con
Transport-Con is a Event-B Model for COMP 6226

## Things to Know
This Event-B Model is for **COMP6226 Coursework**.

The whole Model and Refined Model is completely proved by **SMT Prover** and **ProB Simulator**.

Any question please ask in **issue**.

## How to Use
Download and install [Rodin](http://www.event-b.org/install.html) with SMT, [ProB](https://wiki.event-b.org/index.php/ProB), and [CamilleX](https://wiki.event-b.org/index.php/CamilleX) plugin.

Import Transport-Con into **Rodin**

## Detail Specification
1. An admin adds a new driver to the system
2. An admin adds a new vendor to the system
3. An admin adds a new delivery job by choosing a vendor and assign the package to a driver.
4. An Admin viewing a list of pending, in-progress, and delivered/completed jobs
5. An admin viewing a list of delivery jobs completed by a driver
6. An admin sending a message to a driver while attending a delivery job
7. An admin cancelling a delivery job that is pending
8. A driver viewing the list of their allocated jobs
9. A driver marks a job allocated to them with pending state as in-progress or an in-progress
job as delivered/completed
10. Refine your abstract model by adding a new property, named package size into your 
system. In the next step, you are required to refine your abstract specification by 
amending/adding necessary sets/variables/events that represent the cases that each delivery 
package should have a size. Each driver can only handle a subset of packages (based on 
their vehicle size) and an admin should allocate each package to a driver based on the 
package size.

