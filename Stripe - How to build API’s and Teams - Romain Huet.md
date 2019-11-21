# Stripe - How to build API’s and Teams - Romain Huet
#conferences/APIDays/2019

## Apollo programme.
Margaret Hamilton - coined the term software engineering.
They had to build a team from scratch and had all the problems we typically have.

Code rope memory built by threading wires through magnets.
8 week lead time and highly manual intensive. Any mistakes caused the whole programme to be delayed.

## Stripe
500+ distinct endpoints.
Global team
Business relief on them every day

### Building API’s and Teams
1. Put users first (Build for the users of today, consider your platform of tomorrow)
	1. Talk to users. Don’t make assumptions.
	2. Work backwards. User manual < wireframe < FAQ < Press Release < Customer. Before writing code.
	- [x] Check out Stripes ethos. 
	1. Used IRC channel - still in use.
2. Spend time to make it good (Build for the builders)
	1. Over time you need to evolve and improve, keep at it.
	2. In API design, just like anything, you need to put in the time, effort and love to make it great.
	3. Simplicity - map to real life concepts,.
	4. Composable - building blocks should fit nicely together
	5. Predictable - when you turn on the tap you expect water to come out. You should expect the same outcome of API’s.
	6. They should be backwards compatible by design.
	7. API Design Process
		1. Design Document
		2. API Spec
		3. Endpoints
		4. Events
		5. Parameters
	8. API Review
		1. Platform operations
		2. Developer Experience
		3. Frontend tooling
		4. Security Practices
	9. User Testing
		1. Usability
		2. Experimental Usage
		3. Interviews
	10. Early version release
		1. Beta release
		2. Gated features
	11. API Design Tips
		1. Build in as many opportunities for feedback as possible.
		2. Avoid industry jargon.
		3. Properties as enums
		4. Reflect API request in the response
		5. polymorphic objects
		6. Express changes with verbs. i.e. capture or mark_as_uncollectable
		7. Timestamp parameters names as verbs.
		8. Gated features i.e. A/B testing - make sure you aggressively remove the gated code to ensure the system is maintainable.
		9. Dogfooding. Use your own products.
3. Design your organisation (Can you harness Conways’s Law?)
	1. Remember Conways law.

![](Stripe%20-%20How%20to%20build%20API%E2%80%99s%20and%20Teams%20-%20Romain%20Huet/Photo%2014%20Nov%202019%20at%20104305.jpg)
