# Introduction to DevOPs: Overall Concepts

• Programming

Software is programmed by developers usually one team per application. Or one team per feature for a larger application.

The team is responsible for creatine new functionality and fixing bugs.

• Testing

When there is an existing application, it is important to continually test new features to sure ensure the changes in the code don’t disrupt the existing functionalities.

Developers run tests themselves but they also have other dedicated testers. This process can be very complex as a result there is automated testing (programmes testing the application)

• Release of software

Once the tests are complete The new features can be rolled out to the users. In order to release the application the application must be packaged Into a compressed code and then ran on a server.

• Operations 

In case of a larger existing programme being run on the servers, when the software is released the application is updated and upgraded.

# Traditional Development/Operations vs. DevOps Culture

Traditionally, software development and software operations were handled by separate teams. Each team had a different job—and different priorities. Let’s use an online shopping website as an example.

The traditional software development process The development team builds the software and adds new features. For example, the business asks developers to add a “Pay with PayPal” button. Developers would:
Find out what the feature needs to do.
Write the code.

Test it, often with a separate quality assurance team.
Hand the finished software to the operations team for release. The developers’ main priority was usually: “Build and deliver the features the business needs.”

The traditional software operations process The operations team runs the servers and systems that make the website available to customers. Their responsibilities would include: • Preparing servers and installing software. • Deploying new versions of the website. • Monitoring performance and availability. • Managing backups, security updates, and failures. Their main priority was usually: “Keep the website stable and available.”

Why this could cause problems Both priorities were reasonable, but they could pull the teams in different directions. Developers wanted to introduce changes. Operations wanted to avoid changes that might break a working system. Imagine that the new PayPal feature works on a developer’s computer but fails when operations deploys it to the live website. The developer might say: “It works on my machine.” Operations might respond: “But it doesn’t work on our servers, and we weren’t told it needed another software package.” This separation could lead to: Problem What happened Poor communication Operations discovered requirements or changes late. Different environments Software behaved differently on developers’ computers and live servers. Manual work Deployments involved repeated steps that were slow and easy to get wrong. Large, infrequent releases Many changes arrived together, making problems harder to locate. Unclear responsibility Teams spent time deciding whose problem a failure was. Slow feedback Developers learned about real-world problems long after writing the code. The main weakness was the handover between teams. Each team could complete its own work successfully while the overall delivery process remained slow and unreliable.

Why DevOps was introduced DevOps is a culture in which development and operations work together and share responsibility for delivering and running software. Instead of treating software as something developers finish and then pass to operations, both groups consider its whole life: How will we build it, test it, release it, run it, and improve it? That usually means: • Working together earlier: Operations contributes before deployment day. • Automating repetitive tasks: Tests, infrastructure setup, and deployments become more consistent. • Releasing smaller changes: Each release is easier to understand, check, and recover from. • Using consistent environments: Tools and configuration reduce differences between testing and production. • Monitoring and sharing feedback: Information from the live system helps developers improve the software. • Sharing responsibility: Teams focus on fixing problems and preventing repeats. For the PayPal feature, developers and operations would agree on requirements early, use automated checks, and prepare monitoring and a recovery plan before release. The goal of DevOps is to make delivering changes faster and safer while keeping systems reliable. Tools such as Git, Jenkins, Docker, and Terraform support that goal, but the foundation is how people collaborate—not simply which tools they install.
