# SUMMARY

## Process Management

An interaction is a program in execution. It is a unit of work inside the framework. Program is a latent element, measure is a functioning element. Interaction needs assets to achieve its assignment CPU, memory, I/O, documents Initialization information Process end requires recover of any reusable assets Single-strung cycle has one program counter indicating area of next guidance to execute Process executes directions consecutively, each in turn, until fruition Multi-strung cycle has one program counter for every string Typically framework has many cycles, some client, some working framework running simultaneously on at least one CPUs Concurrency by multiplexing the CPUs among the cycles/strings .The fundamental elements of the OS wrt the cycle the board are : - Allocating assets to measures, - Enabling cycles to share and trade data, - Protecting the assets of each interaction from different cycles and. - Enabling synchronization among measures. Cycle the executives includes different assignments like creation, planning, end of cycles, and a halt . It is the work of OS to deal with every one of the running cycles of the framework. It handles activities by performing errands like interaction planning and like asset portion.
                  



![OS](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2015/06/process-states1.png)



##  System call implementation

A framework call is a way for projects to collaborate with the working framework. ... It gives an interface between an interaction and working framework to permit client level cycles to demand administrations of the working framework. Framework calls are the main passage focuses into the piece framework.

![OS](https://i.stack.imgur.com/tGPV0.png)

Commonly, a number related with every framework call System-call interface keeps a table ordered by these numbers The framework call interface summons the expected framework bring in OS piece and returns status of the framework call and any return esteems The guest need think nothing regarding how the framework call is executed Just necessities to submit to API and get what OS will do thus call Most subtleties of OS interface stowed away from software engineer by API Managed by run-time support library (set of capacities incorporated into libraries included with compiler)


Summary chapter one & two
