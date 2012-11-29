Agenda

# Welcome
-- Who we are

# Podio

## PRINCIPLES

1. Constant evolution of product and platform
1.1 Value for our customers
1.2 Deliver fast & Fail fast. Try stuff out. Protyping. Then perfect
2. Data-driven. A/B testing, measurements
1.1 Smooth transition (from PHP to Rails to JS)
1.2 Leveraging existing infrastructure (no duplicate code)

2. Right tools for the job
2.1. Avoid complexity
2.1 KISS
2.3 Onboard non-JS developers.
2.4 Built on convensions.

3.1 Continuous integration
3.2 Continuous deployment
    3.3. Feature system

## PODIO STACK EVOLUTION
1. Our prototype (PHP)
2. Introduction of API.
3. Project Zeus
3.2 SASS
# CSS
1. SASS
2. Mixins library
3. OOCSS
4. CSS reuse -> modules, themes and layouts

3.3 Server-sided MVC

# WHY CLIENT SIDE

1. Faster and more responsive UX
1.1 Our ambition (vision)
 - Realtime
1.2 User expectations (Facebook comparison)

2. Leverage the power of clients
2. Reuse of components
3. More reliability
	3.1 No state in the DOM 	(SoC)
	3.2 TestingM

# WHY BACKBONE
1. Fit Rails setup.
2. Live on top. For a long time in parallel
1. Easy to use
2. Minimalistic and extensible.
3. Does not lock you in on patterns.
4. A lot of movement in the space. (JavaScript MVC, SproutCore, Knockout)
4. Fits existing infrastructure	 (RESTful when you need it).

# BACKBONE 101 (picture?)
1. Models
2. Collections
3. Views

## Our learnings towards to the PODIO MVC ARCHITECTURE
Drawbacks of the MV* approach in many JS frameworks:
1. Tight binding between Views and Models does not scale
1.2 PodioPicker (store state in memory instead of DOM)
1.2 Single state can influence multiple components
1.3 Arregated state from multiple state-models
1.1 ViewModels vs. StateModels

1. Controllers (one or more)
1.1 Views and Models are not bound
1.2 Single point of responsibility (top-down actions only)
1.3 Context-awareness (specific vs. generic)
1.4 Component management and global state
2. Event Bus
2.1 Decoupled, generic, not context aware components
2.2 Everyone talks, but only controllers respond
3. View helpers
	3.1 Rails conformity

# (JS) Testing
1. Unit Testing (Black Box) of models
2. Unit Testing (White Box) of controllers
3. Acceptance Testing with Capybara/Phantom

# FUTURE
Things we are working on (on going projects)
- modules, AMD, dynamic bundling
2. Real time (the state now)
3. JavaScript and the API.
- Future of Rails
- node.js
- Do we actually need web-servers?



