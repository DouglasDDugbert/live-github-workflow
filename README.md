# live-github-workflow
added github workflow pdf

what goal is the usage of git over any other type of backup or source code management system? why do this at all?

the primary goal of any of this is to decrease the risk of managing source codes needed for custom integrated systems.

using a file server provides the benefit of a single location to direct backups, but provides no other administration.

using a shared folder system like dropbox or google drive provides the benefit of cloud backups, multiple site syncronization,
and a rudimentary amount of version control, but some of the development environments necessary for current control
systems are not easily compatible with them.

developing a workflow around using a source code management / version control system such as git adds all those benefits as well
as a fully-documented history to a system. Using git forces our development team to a higher standard of source code management 
discipline with the long-term benefit of knowing why a system's code was created, and by whom.

workflows specific to a restricted use-case need defined.

folder structure local on a desktop is not relevant. But folder structure from the perspective of repository creation
is very important. How are repositories managed? Our idea is to keep it simple at the expense of storing redundant data.
Some placed manage separate repositories per crestron device control module. At this moment I would shy away from that, until we
reach a point where we are releasing modules to the public.

<div>
<p>Some use-cases to consider:
<ul>
<li>How to start a new program and intoduce the data to the github repo</li>
<li>How to update the repo during development?</li>
<li>What is the process to edit b/c of bugfix?</li>
<li>What is the process to edit b/c of service?</li>
<li>What is the process to edit b/c of system change?</li>
<li>What codes go into GitHub?</li>
</ul>
</p></div>
