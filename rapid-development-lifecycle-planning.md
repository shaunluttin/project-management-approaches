# Introduction

The development of chess went through several phases: 

1. **Romantic**
2. **Scientific**: Tactics, Endgames, Openings, Strategy
3. **Post-Modern**
4. **New Dynamism**

People learning chess (and software) tend to go through simmilar stages.

Strategy is to chess how **lifecycle models** are to software.

> For our purproses, the main function of a lifecycle model is to establish the order in which a project specifies, prototypes, designs, implements, reviews, tests, and performs other activities. (McConnell, 1996)

Magnus Carlsen has reached New Dynamism.

![image](https://user-images.githubusercontent.com/2066637/189397773-305e104c-b450-4a9e-9ea4-1aa288bd1b12.png)

# The Lifecycle Model Menu

Adapted from McConnell, S. (1996).

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
* Throwaway Prototyping^

^ Rapid Development (McConnel, 1996) considers these four to be Best Practices.

# Choosing the Most Rapid Lifecycle for Your Project

Adapted from McConnell, S. (1996).

To choose the most effective lifecycle, first examine your project and answer several questions; then then choose a model that...

### Works with poorly understood requirements

- Q: How well do my customer and I understand the requirements at the beginning of the project? 
- Q: Is our understanding likely to change as we move through the project?
- These models work well when either you or your customer understand the system's requirements pooly;
- or when your customer is prone to change requirements. 
- These models work well with exploratory software development.

### Works with poorly understood architecture

- Q: How well do I understand the system architecture? 
- Q: Am I likely to need to make major architectural changes midway through the project?
- These models work well when you're developing a new application area;
- or when you're developing in a familiar application area but are developing unfamiliar capabilities.

### Produces a highly reliable system

- Q: How much reliability do I need?
- These models tend to produce a system with minimal defects when put into production.

### Produces a system with a large growth envelope

- Q: How much do I need to plan ahead and design ahead during this project for future versions?
- These models let us modify the system in size and diversity over its lifetime; 
- this includes modifying the system in ways that the original developers did not anticipate.

### Manages risks

- Q: How much risk does this project entail? 
- These models help identify and control schedule risk, product risk, and other risks.

### Can be constrained to a predefined schedule

- Q: Am I constrained to a predefined schedule? 
- These models support delivery of software by an immovable drop-dead date.

### Has low overhead

- Q: How much time and toil do I need to use this lifecycle model successfully? 
- Using these models require less management and technical overhead for effective use. 
- This overhead might include planning, status tracking, documentation, package acquisition...
- and other activities that do not directly produce software.

### Requires little manager or developer sophistication

- Q: How much sophistication do I need to use this lifecycle model successfully? 
- Q: These models require little if any training or education to use effectively. 
- That includes the skills to track progress, avoid risks inherent in the model, avoid wasting time using the model,
- basically, to realize the benefits that lead you to use the model in the first place.

### Allows for midcourse corrections

- Q: Do I need to be able to make midcourse corrections? 
- These models support changing significant aspects of the product midway through the development cycle; 
- this does not include changing the product's basic mission but does include extending it.

### Provides customers with progress visibility

- Do I need to provide my customers with visible progress throughout the project? 
- These models automatically generate signs of progress that the customer can use to track the project status.

### Provides management with progress visibility

- Do I Need to provide management with visible progress throughout the project?  
- These models automatically generate signs of progress that management can use to track the project status.

Based on the answers to the questions, we can choose a Lifecycle Model that provides the most rapid approach for our project.

> In general, the more closely you can stick to a linear, waterfall-like approach - and do it effectively - the more rapid your development will be... often it's safer to choose an approach that's more flexible.

# Bibliograph 

McConnell, S. (1996). _Rapid development: Taming wild software schedules._
