
# Introduction

Quoted from Big Ball of Mud http://laputan.org/mud/

> Kent Beck has observed that the way to build software is to: Make it work. Make it right. Make it fast [Beck 1997].
> 
> "Make it work" means that we should focus on functionality up-front, and get something running.
> "Make it right" means that we should concern ourselves with how to structure the system only after we’ve figured out the pieces we need to solve the problem in the first place.
> "Make it fast" means that we should be concerned about optimizing performance only after we’ve learned how to solve the problem, and after we’ve discerned an architecture to elegantly encompass this functionality.
> 
> Once all this has been done, one can consider how to make it cheap.

Maybe at the end of the presentation series we can answer, "What software lifecycle model does that fit? What about a Minimum Viable Product? What lifecycle does that fit?"

# The Lifecycle Model Menu

Adapted from McConnell, S. (1996). Rapid development: Taming wild software schedules.

* Pure Waterfall
* Code-and-Fix
* Spiral^
* Modified Waterfalls
* Evolutionary Prototyping^
* Staged Delivery^
* Evolutionary Delivery^
* Design-to-Schedule
* Design-to-Tools
* Commercial Off-the-Shelf Software

^ Rapid Development considers these four to be Best Practices.

# Choosing the Most Rapid Lifecycle for Your Project

Adapted from McConnell, S. (1996). Rapid development: Taming wild software schedules.

To choose the most effective lifecycle for your project, examine your project and answer several questions:

Works with poorly understood requirements.

- Q: How well do my customer and I understand the requirements at the beginning of the project? 
- Q: Is our understanding likely to change as we move through the project?
- These models work well when either you or your customer understand the system's requirements pooly;
- or when your customer is prone to change requirements. 
- These models work well with exploratory software development.

Works with poorly understood architecture.

- Q: How well do I understand the system architecture? 
- Q: Am I likely to need to make major architectural changes midway through the project?
- These models work well when you're developing a new application area;
- or when you're developing in a familiar application area but are developing unfamiliar capabilities.

Produces a highly reliable system.

- Q: How much reliability do I need?
- These models tend to produce a system with minimal defects when put into production.

Produces a system with a large growth envelope.

- Q: How much do I need to plan ahead and design ahead during this project for future versions?
- These models let us modify the system in size and diversity over its lifetime; 
- this includes modifying the system in ways that the original developers did not anticipate.

Manages risks.

- Q: How much risk does this project entail? 
- These models help identify and control schedule risk, product risk, and other risks.

Can be constrained to a predefined schedule.

- Q: Am I constrained to a predefined schedule? 
- These models support delivery of software by an immovable drop-dead date.

Has Low Overhead

- Q: How much time and toil do I need to use this lifecycle model successfully? 
- Using these models require less management and technical overhead for effective use. 
- This overhead might include planning, status tracking, documentation, package acquisition...
- and other activities that do not directly produce software.

Requires little manager or developer sophistication

- Q: How much sophistication do I need to use this lifecycle model successfully? 
- Q: These models require little if any training or education to use effectively. 
- That includes the skills to track progress, avoid risks inherent in the model, avoid wasting time using the model,
- basically, to realize the benefits that lead you to use the model in the first place.

Allows for midcourse corrections.

- Q: Do I need to be able to make midcourse corrections? 
- These models support changing significant aspects of the product midway through the development cycle; 
- this does not include changing the product's basic mission but does include extending it.

Provides customers with progress visibility.

- Do I need to provide my customers with visible progress throughout the project? 
- These models automatically generate signs of progress that the customer can use to track the project status.

Provides management with progress visibility.

- Do I Need to provide management with visible progress throughout the project?  
- These models automatically generate signs of progress that management can use to track the project status.

Based on the answers to those questions, we can choose a more rapid Lifecycle Model for our project.

> In general, the more closely you can stick to a linear, waterfall-like approach - and do it effectively - the more rapid your development will be... often it's safer to choose an approach that's more flexible.

