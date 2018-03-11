# Base Skeleton

This is a skeleton for all git projects.

All projects should have a README.md.  Put your own specific readme here.  It would be a good idea to include:

 - Purpose of the project:
   - Why does it exist?
   - What does it do differently than other similar projects, if any?
   - What does it do the same?
 - Any specific policies regarding code and architectural design?
   - What code policies are to be adhered to?
   - What design patterns are being used, and which should be used?
 - Any specific policies regarding work flow:
   - Is git flow being used?  What do the branches mean?  Tag policy?
   - Are there specific review requirements?
 - Most importantly, full build and deployment requirements, and any other operational instructions.  It should be detailed enough so that the code can be turned into a runnable project using this guide alone as the starting pont.
   - Any special configuration considerations?
   - What kind of infrastructure services are required?  This includes database schemas, messaging, caches, and filesystem directories needed.
   - Are there any scheduled tasks (cron jobs), long running daemons, or other special tools that need to be executed frequently, infrequently, or all the time?
   - For web applications and services, this would include an overview of webserver requirements and configurations.  How do you scale this application?  How does it work with load balancing?
   - For desktop applications, how do you compile/build this software?  Are there project files?  Any third party libraries required?  What does a deployment look like?  Where do we update the downloadable package?  NSIS scripts?
 - Developers responsible for the code:
   - Credit to author(s)
   - Who should be contacted regarding code, and implementation questions?
   - And if this is a product, who should be contacted in an operational emergency?

Other documents you may want to include:

 - A separate `DEPLOYMENT.md` for deployment/operational information.
 - A `LICENSE.md` that includes licensing information.
 

_Remember to replace this file with your own README.md!_